# Direct3D-
一个基础学习的仓库

## DirectXMath
- `HALF XMConvertFloatToHalf(float Value);`
- `float XMConvertHalfToFloat(HALF Value);`
- `XM_CONSTEXPR float XMConvertToDegrees(float fRadians);`
- `XM_CONSTEXPR float XMConvertToRadians(float fDegrees);`

## XMVECTOR
- `float XM_CALLCONV XMVectorGetX(FXMVECTOR V);`
- `float XM_CALLCONV XMVectorGetY(FXMVECTOR V);`

## ID3D11DeviceContext
- 
```
void OMSetRenderTargets(
  UINT                   NumViews,
  ID3D11RenderTargetView * const *ppRenderTargetViews,
  ID3D11DepthStencilView *pDepthStencilView
);
```
