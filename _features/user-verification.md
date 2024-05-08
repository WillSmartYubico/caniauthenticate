---
title: "User Verification"
description: "First introduced as part of FIDO2, user verification indicates a user verified their ownership of a FIDO authenticator by entering a PIN in the client or otherwise activating the authenticator with a PIN or biometric.  User presence is a mandatory feature for all FIDO2 authenticators."
category: ctap2
keywords: uv, clientpin
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
            "a23":"y"
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