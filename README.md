# RIS Builder v1

Android APK project for visual management of the RIS Telegram bot.

## Included
- Dark RIS dashboard
- Commands manager
- Visual workflow editor
- Custom variables
- Broadcasts
- Groups/users/moderation/economy/statistics/settings sections
- Create `/приз` as a visual workflow
- Launch / stop / restart through Termux RUN_COMMAND
- No Python editing required for the intended workflow

## Termux setup
1. Install Termux from an official source.
2. In Termux create `~/.termux/termux.properties` and set:
   `allow-external-apps=true`
3. In Android settings grant RIS Builder the additional permission:
   `Run commands in Termux environment`.
4. Put the RIS engine at `~/bot.py`.
5. The app's Launch button runs `python ~/bot.py` in Termux.

The project uses Jetpack Compose and can be opened in Android Studio and built as an APK.
