# Earth Eccentricity Simulation
地球の公転の角度から地球の離心率を求める

## Requirements

- Python 3.11 以上（3.10以降を推奨）
- Jupyter Notebook

## Installation

### 1. リポジトリを取得

```bash
git clone https://github.com/NEKOHUKURO/earth_eccentricity_simulation.git
cd earth_eccentricity_simulation
```

### 2. 仮想環境の作成（推奨）



```bash
python -m venv .venv
.venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. 必要ライブラリをインストール

```bash
pip install numpy scipy sympy mpmath matplotlib plotly jupyter
```

## Running

Jupyter Notebook を起動します。

```bash
jupyter notebook
```

または

```bash
jupyter lab
```

ブラウザで

```
fitting_comp.ipynb
```

を開き、セルを上から順番に実行してください。

## Contents

Notebookでは以下を行います。

- 楕円軌道上の面積計算
- 近日点・遠日点を考慮した数式導出
- SymPyによる解析微分
- SciPyによるパラメータフィッティング
- Plotlyによる結果の可視化

## License

MIT License