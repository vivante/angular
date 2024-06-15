## API Report File for "@angular/platform-browser-dynamic"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { Compiler } from '@angular/core';
import { CompilerFactory } from '@angular/core';
import { CompilerOptions } from '@angular/core';
import { PlatformRef } from '@angular/core';
import { StaticProvider } from '@angular/core';
import { Version } from '@angular/core';

// @public @deprecated (undocumented)
export class JitCompilerFactory implements CompilerFactory {
    // (undocumented)
    createCompiler(options?: CompilerOptions[]): Compiler;
}

// @public (undocumented)
export const platformBrowserDynamic: (extraProviders?: StaticProvider[] | undefined) => PlatformRef;

// @public (undocumented)
export const VERSION: Version;

// (No @packageDocumentation comment for this package)

```