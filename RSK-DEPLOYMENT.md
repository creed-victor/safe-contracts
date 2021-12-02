# RSK Network Deployment Logs

Deployed 1.3.0 first time.

```bash
sending eth to create2 contract deployer address (0x3fab184622dc19b6109349b94811493bf2a45362) (tx: 0xd707295af11a15c69a6036a062b88e5afe238a17bf6355ae8d2a3b29865d3ac1)...
deploying create2 deployer contract (at 0x4e59b44847b379578588920ca78fbf26c0b4956c) using deterministic deployment (https://github.com/Arachnid/deterministic-deployment-proxy) (tx: 0xeddf9e61fb9d8f5111840daef55e5fde0041f5702856532cdbb5a02998033d26)...
deploying "SimulateTxAccessor" (tx: 0xe83adb67debab2f24485dc698220fe232df2b94ddbceb25d97b636cd0f53aa0f)...: deployed at 0x59AD6735bCd8152B84860Cb256dD9e96b85F69Da with 282175 gas
deploying "GnosisSafeProxyFactory" (tx: 0xb818a86e5cee4d9afda0f845808a4a90d11aa08987dcd16ba1ddfb13f7fba808)...: deployed at 0xE89ce3bcD35bA068A9F9d906896D3d03Ad5C30EC with 1050050 gas
deploying "DefaultCallbackHandler" (tx: 0x31be2dae1ff676165f96f6d8a43cb33009b972f840c4b318e615d1cf256806cb)...: deployed at 0x1AC114C2099aFAf5261731655Dc6c306bFcd4Dbd with 650373 gas
deploying "CompatibilityFallbackHandler" (tx: 0x10e59803340fdec4761126c87256dfda3ac16d3d02b1af9cae6145f958a6db7f)...: deployed at 0xe16bA5bF81E5BB113e4752E4fdC20351d796fB24 with 1502931 gas
deploying "CreateCall" (tx: 0x3bbe91ba5075bd41de738ebdee53b2511a5c5d60449b1fa794a7b4b9490d3cca)...: deployed at 0x7cbB62EaA69F79e6873cD1ecB2392971036cFAa4 with 348486 gas
deploying "MultiSend" (tx: 0xa161862f4e5f7c13fe058c63be1d71d1d300615426afd91be0d02471b819f031)...: deployed at 0xA238CBeb142c10Ef7Ad8442C6D1f9E89e07e7761 with 222816 gas
deploying "MultiSendCallOnly" (tx: 0x276aa9474bb4bc997d3905a8e3cc081a41b66101d6963160af433e084baf1aae)...: deployed at 0x40A2aCCbd92BCA938b02010E17A5b8929b49130D with 163130 gas
deploying "SignMessageLib" (tx: 0x4cfe2e5fb4ec0975e9a99541a299e35651a1aab80ac00ee1de0bbf8a35ccdf30)...: deployed at 0x5495e1dE99d9eFCcf131cF49B2453F410128B1b1 with 311377 gas
deploying "GnosisSafeL2" (tx: 0x1811fb9b2950522d381d34c48c7d935ab28c9a5923d929044083365a5dcab007)...: deployed at 0xE51abdf814f8854941b9Fe8e3A4F65CAB4e7A4a8 with 6392261 gas
deploying "GnosisSafe" (tx: 0x8f1e9f994f98338a96af094bf8f75a2ddcce96938cfad30e14dff67121b0f453)...: deployed at 0xb4A7C7da1631CF60A2Cf23ABc86986f99a1A7f70 with 6166552 gas
Verification status for SimulateTxAccessor: FAILURE
Verification status for GnosisSafeProxyFactory: SUCCESS
Verification status for DefaultCallbackHandler: SUCCESS
Verification status for CompatibilityFallbackHandler: SUCCESS
Verification status for CreateCall: SUCCESS
Verification status for MultiSend: FAILURE
Verification status for MultiSendCallOnly: SUCCESS
Verification status for SignMessageLib: SUCCESS
Verification status for GnosisSafeL2: SUCCESS
Verification status for GnosisSafe: SUCCESS
```

# RSK Testnet Deployment Logs

v1.3.0 was already deployed for testnet.

```bash
reusing "SimulateTxAccessor" at 0x59AD6735bCd8152B84860Cb256dD9e96b85F69Da
reusing "GnosisSafeProxyFactory" at 0xa6B71E26C5e0845f74c812102Ca7114b6a896AB2
reusing "DefaultCallbackHandler" at 0x1AC114C2099aFAf5261731655Dc6c306bFcd4Dbd
reusing "CompatibilityFallbackHandler" at 0xf48f2B2d2a534e402487b3ee7C18c33Aec0Fe5e4
reusing "CreateCall" at 0x7cbB62EaA69F79e6873cD1ecB2392971036cFAa4
reusing "MultiSend" at 0xA238CBeb142c10Ef7Ad8442C6D1f9E89e07e7761
reusing "MultiSendCallOnly" at 0x40A2aCCbd92BCA938b02010E17A5b8929b49130D
reusing "GnosisSafeL2" at 0x3E5c63644E683549055b9Be8653de26E0B4CD36E
reusing "GnosisSafe" at 0xd9Db270c1B5E3Bd161E8c8503c55cEABeE709552
Verification status for SimulateTxAccessor: FAILURE
Verification status for GnosisSafeProxyFactory: SUCCESS
Verification status for DefaultCallbackHandler: SUCCESS
Verification status for CompatibilityFallbackHandler: SUCCESS
Verification status for CreateCall: SUCCESS
Verification status for MultiSend: FAILURE
Verification status for MultiSendCallOnly: SUCCESS
Verification status for GnosisSafeL2: SUCCESS
Verification status for GnosisSafe: SUCCESS
```