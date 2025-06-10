---
keywords: uv, alwaysuv
title: Always UV
notes_by_num:
  "1": FIDO2 Support provided by Windows' webauthn.dll.
  "2": AlwaysUV works for registration, but not authentication.
description: Ensures that the authenticator will always perform user verification when creating or using a credential, even if it is not requested by the relying party.  If this is not supported, the platform may not know it needs to prompt for a PIN, which will cause WebAuthn as a second factor flows to fail if it's enabled.
last_test_date: 2025-05-13
category: ctap21
notes: Always UV support is important for compliance with FIPS 140-3.
links:
  YubiKey Technical Manual on Always UV: https://docs.yubico.com/hardware/yubikey/yk-tech-manual/5.7-firmware-specifics.html#always-uv
stats:
  safari:
    ios:
      latest: a
    ipados:
      latest: a
    macos:
      latest: a
  firefox:
    windows11:
      latest: "y"
    windows:
      latest: a
    android:
      latest: "y"
    macos:
      latest: a
  chrome:
    windows11:
      latest: "y"
    windows:
      latest: a
    android:
      latest: u
    macos:
      latest: "y"

---
