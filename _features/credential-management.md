---
title: "Credential Management"
description: "Credential management allows for removing or renaming individual discoverable credentials rather requiring a full FIDO reset to remove them all."
category: ctap2
keywords: ctap2
last_test_date: "2024-05-08"
test_url: "/tests/template.html"
test_results_url: ""
stats: {
    chrome: {
        windows-10: {
            "124":"n #1 #2"
        },
        windows-11: {
            "124":"n #1 #2"
        },
        macos: {
            "124":"y"
        },
        android: {
            "124":"n"
        },
        linux: {
            "124":"y"
        }
    },
    firefox: {
        windows-10: {
            "123":"n #3"
        },
        windows-11: {
            "123":"n #3"
        },
        macos: {
            "123":"n #3"
        },
        linux: {
            "123":"n #3"
        }
    },
    safari: {
        macos: {
            "17.4.1":"n"
        },
        ios: {
            "17.4.1":"n"
        }
    }
}
notes: "This is a global note."
notes_by_num: {
    "1": "FIDO2 Support provided by Windows' webauthn.dll.",
    "2": "Credential management in Windows requires elevated permissions and should not be attempted with a web browser.",
    "3": "Bugzilla entry: https://bugzilla.mozilla.org/show_bug.cgi?id=1819346"
}
links: {
}
---