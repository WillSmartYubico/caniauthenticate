---
title: "Always UV"
description: "Ensures that the authenticator will always perform user verification when creating or using a credential, even if it is not requested by the relying party."
category: ctap21
keywords: uv, alwaysuv
last_test_date: "2024-05-13"
test_url: "/tests/template.html"
test_results_url: ""
stats: {
    chrome: {
        windows-10: {
            "124":"n #1"
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
            "124":"u"
        }
    },
    firefox: {
        windows-10: {
            "123":"u #1"
        },
        windows-11: {
            "123":"y #1"
        },
        macos: {
            "123":"n #2"
        },
        linux: {
            "123":"u"
        }
    },
    safari: {
        macos: {
            "17.4.1":"n #2"
        },
        ios: {
            "17.4.1":"y"
        }
    }
}
notes: "Always UV support is important for compliance with FIPS 140-3."
notes_by_num: {
    "1": "FIDO2 Support provided by Windows' webauthn.dll.",
    "2": "AlwaysUV works for registration, but not authentication."
}
links: {
    "YubiKey Technical Manual on Always UV":"https://docs.yubico.com/hardware/yubikey/yk-tech-manual/5.7-firmware-specifics.html#always-uv"
}
---