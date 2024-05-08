---
title: "Large Blob Storage"
description: "Large blob storage is a facility for storing a (relatively) large amount of data (minimum of 1kb, 1-4kb typical) on a FIDO2 authenticator.  Typically used for storing data related to a FIDO2 credential, like an SSH certificate."
category: ctap21
keywords: largeblob, blob, storage
last_test_date: "2024-05-08"
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
            "124":"n"
        },
        linux: {
            "124":"y"
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
    "Large Blob Demo":"https://webauthn-large-blob.glitch.me/"
}
---