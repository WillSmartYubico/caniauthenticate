---
title: "Credential Protection"
description: "Also known as credProtect, the Credential Protection extension supports fine-grained control over the circumstances when an authenticator allow a specific discoverable credential to be used."
category: CTAP2.1 
keywords: ctap2.1, ctap2.1-pre, rk
last_test_date: "2024-05-08"
test_url: "/tests/template.html"
test_results_url: ""
stats: {
    chrome: {
        windows-10: {
            "124":"u #1"
        },
        windows-11: {
            "124":"u #1"
        },
        macos: {
            "124":"u"
        },
        android: {
            "124":"u"
        },
        linux: {
            "124":"a #2"
        }
    }
    firefox: {
        windows-10: {
            "123":"u #1"
        },
        windows-11: {
            "123":"u #1"
        },
        macos: {
            "123":"u"
        },
        android: {
            "123":"u"
        },
        linux: {
            "123":"u"
        },
    }
    safari: {
        macos: {
            "17.4.1":"u"
        },
        ios: {
            "17.4.1":"u"
        }
    },
}
notes: ""
notes_by_num: {
    "1": "FIDO2 Support provided by Windows' webauthn.dll."
}
links: {
    "CTAP2.1 specification: Feature-Specific Descriptions and Actions":"https://fidoalliance.org/specs/fido-v2.1-ps-20210615/fido-client-to-authenticator-protocol-v2.1-ps-errata-20220621.html#op-getassn-step-locate-credentials",
    "Chromium's credProtect behaviour in WebAuthn":"https://chromium.googlesource.com/chromium/src/+/HEAD/content/browser/webauth/cred_protect.md"
}
---