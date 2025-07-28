# Session
I need help please for my problem
I got this message and line code : 
ERROR 2025-07-28T06:17:15.608Z main_renderer: ConversationController failed to load: TypeError: key.startsWith is not a function
    at PubKey.isBlinded (/Applications/Session.app/Contents/Resources/app.asar/ts/session/types/PubKey.js:108:29)
    at Object.isContactToStoreInWrapper (/Applications/Session.app/Contents/Resources/app.asar/ts/session/utils/libsession/libsession_utils_contacts.js:17:86)
    at load (/Applications/Session.app/Contents/Resources/app.asar/ts/session/conversations/ConversationController.js:357:84)
    at async Promise.all (index 0)
    at async /Applications/Session.app/Contents/Resources/app.asar/ts/mains/main_renderer.js:150:9
/Applications/Session.app/Contents/Resources/app.asar/ts/util/logger/renderer_process_logging.js:78 INFO  2025-07-28T06:17:15.609Z Cleanup: starting...
/Applications/Session.app/Contents/Resources/app.asar/ts/util/logger/renderer_process_logging.js:78 INFO  2025-07-28T06:17:15.610Z Cleanup: Found 0 messages for cleanup
/Applications/Session.app/Contents/Resources/app.asar/ts/util/logger/renderer_process_logging.js:78 INFO  2025-07-28T06:17:15.610Z Cleanup: complete
/Applications/Session.app/Contents/Resources/app.asar/ts/util/logger/renderer_process_logging.js:78 INFO  2025-07-28T06:17:15.610Z listening for registration events
/Applications/Session.app/Contents/Resources/app.asar/ts/util/logger/renderer_process_logging.js:78 INFO  2025-07-28T06:17:15.611Z connect
/Applications/Session.app/Contents/Resources/app.asar/ts/util/logger/renderer_process_logging.js:78 ERROR 2025-07-28T06:17:15.611Z Top-level unhandled promise rejection: TypeError: key.startsWith is not a function
    at PubKey.isBlinded (/Applications/Session.app/Contents/Resources/app.asar/ts/session/types/PubKey.js:108:29)
    at Object.isContactToStoreInWrapper (/Applications/Session.app/Contents/Resources/app.asar/ts/session/utils/libsession/libsession_utils_contacts.js:17:86)
    at load (/Applications/Session.app/Contents/Resources/app.asar/ts/session/conversations/ConversationController.js:357:84)
    at async Promise.all (index 0)
    at async /Applications/Session.app/Contents/Resources/app.asar/ts/mains/main_renderer.js:150:9
background.html:1 Uncaught (in promise) TypeError: key.startsWith is not a function
    at PubKey.isBlinded (/Applications/Session.app/Contents/Resources/app.asar/ts/session/types/PubKey.js:108:29)
    at Object.isContactToStoreInWrapper (/Applications/Session.app/Contents/Resources/app.asar/ts/session/utils/libsession/libsession_utils_contacts.js:17:86)
    at load (/Applications/Session.app/Contents/Resources/app.asar/ts/session/conversations/ConversationController.js:357:84)
    at async Promise.all (/Applications/Session.app/Contents/Resources/app.asar/index 0)
    at async /Applications/Session.app/Contents/Resources/app.asar/ts/mains/main_renderer.js:150:9

    I need help please to solve this problem, in the chat I downloaded a file but didn't sent it and I close the app because it didn't want to delete it and since this , my Session app don't want to open, it freeze on the logo
    Can someone help me please
