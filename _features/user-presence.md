---
title: "User Presence"
description: "First introduced as part of U2F, user presence indicates a user interacted with a FIDO authenticator.  User presence is a mandatory feature for all FIDO authenticators."
category: ctap1
keywords: u2f, up
last_test_date: "2024-05-07"
test_url: "/tests/template.html"
test_results_url: ""
stats: {
    chrome: {
        windows-10: {
            "124":"y #1"
        },
        windows-11: {
            "124":"y #1"
        },
        macos: {
            "124":"y"
        },
        android: {
            "124":"y"
        },
        linux: {
            "124":"y"
        }
    },
    firefox: {
        windows-10: {
            "123":"y #1"
        },
        windows-11: {
            "123":"y #1"
        },
        macos: {
            "123":"y"
        },
        linux: {
            "123":"y"
        }
    },
    safari: {
        macos: {
            "17.4.1":"y"
        },
        ios: {
            "17.4.1":"y"
        }
    }
}
notes: ""
notes_by_num: {
        "1": "FIDO2 Support provided by Windows' webauthn.dll."
}
links: {
}
---