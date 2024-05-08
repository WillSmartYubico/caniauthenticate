---
title: "HMAC-Secret extension"
description: "Also known as hmac-secret, the HMAC Secret Extension exposes two secrets to platform per credential, and is required for the implementation of the WebAuthn prf extension using a FIDO2 security key."
category: ctap2
keywords: extension, hmac, hmac-secret, prf
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
            "124":"y"
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
            "17.4.1":"u"
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
    "Can I use: @font-face Web fonts":"https://www.caniuse.com/#feat=fontface",
    "MDN: @font-face":"https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face"
}
---