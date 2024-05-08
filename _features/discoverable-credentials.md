---
title: "Discoverable Credentials"
description: "Discoverable credentials are credentials that can be listed by the client during an authentication ceremony. This enables authentication without having to enter the username, which is sometimes referred to as a usernameless authentication flow.  Discoverable credentials that also require User Verification are often referred to as passkeys."
category: ctap2
keywords: rk, passkey, usernameless
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
            "123 / 22H2":"y"
        },
        windows-11: {
            "123 / 23H2":"y"
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