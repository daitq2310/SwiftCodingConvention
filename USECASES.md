# Use Cases

This use cases is used in Viettel Digital.

## Table of Contents

* [Create New Modules](#create-new-modules)
  * [Cores](#cores)
  * [Commons](#commons)
  * [Features](#features)
* [Import Modules](#import-modules)
  * [Core Modules](#core-modules)
    * [CoreUIKit](#coreuikit)
    * [CoreUtilsKit](#coreutilskit)
    * [CoreNetworkKit](#corenetworkkit)
    * [CoreDatabaseKit](#coredatabasekit)
  * [Common Modules](#common-modules)
    * [Common Views](#common-views)
* [Images Loading](#images-loading)


## Create New Modules

To create new modules, put them to the right group (`core`, `commons`, `features`) and follow the below checklist.
- Language: `Swift` (do not use `Objective-C` anymore).
- Bitcode: Change to `NO` if you use Pods.
- Development Team: `Viettel Corporation`.
- Beginning Version: `1.0.0`.
- Beginning Build: `1`.
- Target Version: `9.0`.
- iOS Development Target Version: `9.0`.
- Device: `iPhone`.
- Configuration:
  * `Debug`.
  * `beta debug`.
  * `uat debug`.
  * `alpha debug`.
  * `staging debug`.
  * `production debug`.
  * `Release`.
  * `beta`.
  * `uat`.
  * `alpha`.
  * `staging`.
  * `production`.

### Cores

- Display Name: `Core` + `Core Name` + `Kit`.

Example: `CoreUIKit`.

- Organization Name: `ViettelPay App Team`.

- Bundle Identifier: `com.vietteldigital.` + `DisplayName`.

Example: `com.vietteldigital.CoreUIKit`.

### Commons

- Display Name: `Common` + `Common Name`.

Example: `CommonViews`.

- Organization Name: `ViettelPay App Team`.

- Bundle Identifier: `com.vietteldigital.` + `DisplayName`.

Example: `com.vietteldigital.CommonViews`.

### Features

- Display Name: Depend on Development Team, but have to follow the below requirement:
  * Using names based on roles, not types.
  * Using terms that don't surprise experts or confuse beginners.

- Organization Name: Depend on Development Team.

Example: `ViettelPay App Team`, `Mobile App Team`...

- Bundle Identifier: `com.vietteldigital.` + `DisplayName`.

Example: `com.vietteldigital.Authentication`.

## Import Modules

### Core Modules

#### CoreUIKit

- For UI and follow [VDS Design System](https://viettelpay.design), just import `CoreUIKit`.

#### CoreUtilsKit

- `CoreUtilsKit` provides utils functions.

#### CoreNetworkKit

- For Network, use `CoreNetworkKit`.

#### CoreDatabaseKit

- Import `CoreDatabaseKit` to access Database.

### Common Modules

#### Common Views

Comming soon.

## Image Loading

Because [KingFisher](https://github.com/onevcat/Kingfisher) just supports iOS 10.0+ so We'll continue to use [SDWebImage](https://github.com/SDWebImage/SDWebImage) to load image.
