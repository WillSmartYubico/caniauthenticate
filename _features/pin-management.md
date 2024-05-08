---
title: "PIN management"
description: "PIN management indicates that the client provides some mechanism for the user to set or change a PIN.  Typically only required when a user registers with an RP that requires user verification, but a PIN has not already been configured."
category: ctap2
keywords: uv, clientpin, pin
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
            "123":"y #!"
        },
        macos: {
            "123":"n"
        },
        linux: {
            "a23":"n"
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
notes: ""
notes_by_num: {
    "1": "FIDO2 Support provided by Windows' webauthn.dll."

}
links: {
}
---