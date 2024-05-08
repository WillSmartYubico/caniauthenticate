---
title: "Credential Protection"
description: "Also known as credProtect, the Credential Protection extension supports fine-grained control over the circumstances when an authenticator allow a specific discoverable credential to be used."
category: ctap21 
keywords: ctap21,  rk
tags: ctap21, ctap21-pre
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
            "123":"y #1"
        },
        windows-11: {
            "123":"y #1"
        },
        macos: {
            "123":"y"
        },
        android: {
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
    "CTAP2.1 specification: Feature-Specific Descriptions and Actions":"https://fidoalliance.org/specs/fido-v2.1-ps-20210615/fido-client-to-authenticator-protocol-v2.1-ps-errata-20220621.html#op-getassn-step-locate-credentials",
    "Chromium's credProtect behaviour in WebAuthn":"https://chromium.googlesource.com/chromium/src/+/HEAD/content/browser/webauth/cred_protect.md"
}
---