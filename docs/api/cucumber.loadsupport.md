<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@cucumber/cucumber](./cucumber.md) &gt; [loadSupport](./cucumber.loadsupport.md)

## loadSupport() function

Load support code for use in test runs.

<b>Signature:</b>

```typescript
export declare function loadSupport(options: ILoadSupportOptions, environment?: IRunEnvironment): Promise<ISupportCodeLibrary>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  options | [ILoadSupportOptions](./cucumber.iloadsupportoptions.md) | Subset of <code>IRunnableConfiguration</code> required to find the support code. |
|  environment | [IRunEnvironment](./cucumber.irunenvironment.md) | Project environment. |

<b>Returns:</b>

Promise&lt;ISupportCodeLibrary&gt;
