# Changelog

## 1.1.0 (2023-11-01)

### Features
- Adding TOTP support (See [#31](https://github.com/aws-amplify/amplify-ui-swift-authenticator/pull/43))

## 1.0.6 (2023-09-14)

### Misc. Updates
- Updating code to support Amplify 2.16+. However, **TOTP** workflows are **not** yet supported.

## 1.0.5 (2023-08-31)

### Bug Fixes
- Fixing required Sign Up attributes being displayed as optionals
- Fixing Sign Up fields not being populated when providing a `signUpContent`
- Fixing DatePicker being interactable while invisible, plus not displaying previous dates.

## 1.0.4 (2023-08-22)
### Bug Fixes
- Adding missing label when displaying a `.custom()` Sign Up field.

## 1.0.3 (2023-08-17)

### Bug Fixes
- Fixing wrong date format being submitted when displaying `SignUpField` of type `date` (See [#31](https://github.com/aws-amplify/amplify-ui-swift-authenticator/pull/31))

## 1.0.2 (2023-07-25)

### Misc. Updates
- Pinning the Amplify version up to 2.15.x

## 1.0.1 (2023-06-15)

### Bug Fixes
- Fixing issues with Sign Up fields (See [#25](https://github.com/aws-amplify/amplify-ui-swift-authenticator/pull/25)).
  - Removing duplicated fields in the array provided to `Authenticator.signUpFields(_:)`
  - Preventing fields of type `.phoneNumber` from saving an incomplete phone number if only the dialling code is set.
- Fixing Xcode 15 beta compilation error (See [#24](https://github.com/aws-amplify/amplify-ui-swift-authenticator/pull/24), thanks @RowbotNZ!)


## 1.0.0 (2023-05-24)

### Initial release of Amplify UI Authenticator for Swift UI

Amplify Authenticator provides a complete drop-in implementation of an authentication flow for your application using [Amplify Authentication](https://docs.amplify.aws/lib/auth/getting-started/q/platform/ios/).

More information on setting up and using the component is in the [documentation](https://ui.docs.amplify.aws/swift/connected-components/authenticator).
