---
sidebar_label: "滴答图书馆"
sidebar_position: 18
---

# Class: TickLibrary

## Table of contents

### Constructors

- [constructor](TickLibrary#constructor)

### Methods

- [getFeeGrowthInside](TickLibrary#getfeegrowthinside)

## Constructors

### constructor

• `Private` **new TickLibrary**()

Cannot be constructed.

#### Defined in

[utils/tickLibrary.ts:25](https://github.com/SwapX/v3-sdk/blob/08a7c05/src/utils/tickLibrary.ts#L25)

## Methods

### getFeeGrowthInside

▸ `Static` **getFeeGrowthInside**(`feeGrowthOutsideLower`, `feeGrowthOutsideUpper`, `tickLower`, `tickUpper`, `tickCurrent`, `feeGrowthGlobal0X128`, `feeGrowthGlobal1X128`): `default`[]

#### Parameters

| Name                    | Type               |
| :---------------------- | :----------------- |
| `feeGrowthOutsideLower` | `FeeGrowthOutside` |
| `feeGrowthOutsideUpper` | `FeeGrowthOutside` |
| `tickLower`             | `number`           |
| `tickUpper`             | `number`           |
| `tickCurrent`           | `number`           |
| `feeGrowthGlobal0X128`  | `default`          |
| `feeGrowthGlobal1X128`  | `default`          |

#### Returns

`default`[]

#### Defined in

[utils/tickLibrary.ts:27](https://github.com/SwapX/v3-sdk/blob/08a7c05/src/utils/tickLibrary.ts#L27)
