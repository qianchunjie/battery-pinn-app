# 🔋 PINN 电池热参数反演与实时监控系统

基于物理信息神经网络（Physics-Informed Neural Networks, PINN）的锂电池热参数反演与内部温度场重构系统。

## 功能
- 一维瞬态热传导方程（Heat Equation）的 PINN 求解
- 热扩散系数 α 的参数自适应反演（SOH 估算）
- 含噪稀疏传感器数据下的内部温度场重构
- 3D 电池单体热场可视化（数字孪生演示）

## 运行方式
```bash
pip install -r requirements.txt
streamlit run battery_app.py
```

## 技术栈
- Streamlit
- PyTorch
- Plotly / Matplotlib
