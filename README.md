<p align="center">
    <img src="https://raw.githubusercontent.com/abennouna/capacitor-native-compass/master/logo.svg" width="640">
</p>

Capacitor plugin for an easy compass using the native device sensors.

<docgen-index>

- [Install](#install)
- [API](#api)
  - [getCurrentHeading()](#getcurrentheading)

</docgen-index>

## Install

```bash
npm install @abennouna/capacitor-native-compass
npx cap sync
```

## API

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### getCurrentHeading()

```typescript
getCurrentHeading() => Promise<{ value: number; }>
```

Returns the current compass heading in degrees.
On iOS, the heading is updated in the background, and the latest value is returned.
On Android, the heading is calculated when the method is called.
Not implemented on Web.

**Returns:** <code>Promise&lt;{ value: number; }&gt;</code>

--------------------

</docgen-api>
