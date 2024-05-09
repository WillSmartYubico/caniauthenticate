---
title: "Credential Blob Storage"
description: "Large blob storage is a facility for storing a small amount of data per credential (typically a multiple of 32 bytes) on a FIDO2 authenticator.  Typically used for storing something like a certificate hash used to verify a trusted certificate."
category: ctap21
keywords: credblob, blob, storage
last_test_date: "2024-05-09"
test_url: "/tests/template.html"
test_results_url: ""
stats: {
    chrome: {
        windows-10: {
            "124":"u #1"
        },
        windows-11: {
            "124":"y #1"
        },
        macos: {
            "124":"y"
        },
        android: {
            "124":"n"
        },
        linux: {
            "124":"u"
        }
    },
    firefox: {
        windows-10: {
            "123":"n #1"
        },
        windows-11: {
            "123":"n #1"
        },
        macos: {
            "123":"n"
        },
        linux: {
            "123":"n"
        }
    },
    safari: {
        macos: {
            "17.4.1":"n"
        },
        ios: {
            "17.4.1":"u"
        }
    }
}
notes: "This is a global note."
notes_by_num: {
    "1": "FIDO2 Support provided by Windows' webauthn.dll."
}
links: {
    "WebAuthn Test App":"https://webauthntest.identitystandards.io/"
}
---