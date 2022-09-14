# ProConStockChecker

# SetUp

1. 仮想環境を構築
`python -m venv .venv`

2. 仮想環境を有効に
`source .venv/bin/activate`

3. パッケージのインストール
`pip install -r requirements.txt`

あとは`YOUR_NOTIFY_TOKEN`などの設定をすればOK

例) 

ターミナル: `export YOUR_NOTIFY_TOKEN="hogehgoe"`

Python: `os.environ['YOUR_NOTIFY_TOKEN'] = 'hogehoge'`
