<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@office-iss/react-native-win32](./react-native-win32.md) &gt; [GradientColorStop](./react-native-win32.gradientcolorstop.md)

## GradientColorStop type

A color stop within a gradient. The values can either be other color values such as 'red', or a value thats already gone through processColor Note: Currently we only support color stops from 0 to 1. (Where 0 is the gradient start, 1 is gradient end)

<b>Signature:</b>

```typescript
export type GradientColorStop = {
  color: string /*ColorValue*/ | number /*ProcessedColorValue*/;
  offset: 0 | 1;
};
```