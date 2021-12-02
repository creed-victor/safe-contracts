# RSK Network Deployment Logs

Deployed 1.3.0 first time.

```bash
sending eth to create2 contract deployer address (0x3fab184622dc19b6109349b94811493bf2a45362) (tx: 0xd707295af11a15c69a6036a062b88e5afe238a17bf6355ae8d2a3b29865d3ac1)...
deploying create2 deployer contract (at 0x4e59b44847b379578588920ca78fbf26c0b4956c) using deterministic deployment (https://github.com/Arachnid/deterministic-deployment-proxy) (tx: 0xeddf9e61fb9d8f5111840daef55e5fde0041f5702856532cdbb5a02998033d26)...
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