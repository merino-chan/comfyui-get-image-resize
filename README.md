# comfyui-get-image-resize
【ComfyUI Subgraph】get image resize（画像リサイズ解像度計算）

■ 1. 概要
入力された画像のオリジナルサイズを元に、指定した数値で拡大（掛け算）または縮小（割り算）を行い、新しい解像度（Width / Height）を自動で計算して出力するサブグラフです。

・Multiplication = 1 （拡大・掛け算）
・Division = 2 （縮小・割り算）

■ 2. 必須カスタムノード (Required Custom Nodes)
このサブグラフを動作させるには、以下のカスタムノードが事前に必要です。
ComfyUI-Manager等からインストールし、各作者のライセンスに従ってください。

① rgthree-comfy (作者: rgthree)
   - 対象ノード: Power Puter (rgthree)
   - ライセンス: MIT License
   ※ノード内でのPythonスクリプトによる解像度計算に使用しています。

② ComfyUI-Easy-Use (または各種拡張ノードパック)
   - 対象ノード: easy int, PreviewAny, LatentToWidthHeight
   ※数値入力やプレビュー、解像度取得に使用しています。

■ 3. ワークフロー（ノードの組み合わせ）のライセンス
このサブグラフの「ノードの組み合わせ（レシピ）」は、発足者の責任およびオリジナルの記録として、以下のMITライセンスのもとで公開します。

Copyright (c) 2026 [merino-chan]

・ライセンス: MIT License
この著作権表示（上記の一行）を含めていただくことを条件に、商用利用、改変、ご自身のワークフローへの組み込み、再配布などを自由に許可します。

■ 4. 免責事項 (Disclaimer)
依存している外部カスタムノードの動作、および本サブグラフの使用によって生じたあらゆるトラブル・損害について、オリジナル制作者は一切の責任を負いません。各自の責任においてご利用ください。


English Translation
[ComfyUI Subgraph] get image resize (Image Resize Resolution Calculation)

■ 1. Overview
This subgraph automatically calculates and outputs the new resolution (Width / Height) by scaling the input image up (multiplication) or down (division) by a specified value based on its original size.

・Multiplication = 1 (Enlargement/Multiplication)
・Division = 2 (Reduction/Division)

■ 2. Required Custom Nodes
To run this subgraph, the following custom nodes must be installed in advance.
Install them from ComfyUI-Manager or similar sources, and follow the respective authors’ licenses.

① rgthree-comfy (Author: rgthree)
   - Target Node: Power Puter (rgthree)
   - License: MIT License
   *Used for resolution calculations via Python scripts within the node.

② ComfyUI-Easy-Use (or various extension node packs)
   - Target Nodes: easy int, PreviewAny, LatentToWidthHeight
   *Used for numerical input, previews, and obtaining resolution values.

■ 3. Workflow (Node Combination) License
The “node combination (recipe)” in this subgraph is published under the following MIT License as a record of the original work and under the responsibility of the creator.

Copyright (c) 2026 [merino-chan]

・License: MIT License
Provided that you include this copyright notice (the single line above), you are freely permitted to use this for commercial purposes, modify it, incorporate it into your own workflows, redistribute it, and more.

■ 4. Disclaimer
The original creator assumes no responsibility whatsoever for the behavior of any external custom nodes on which this subgraph depends, or for any problems or damages arising from the use of this subgraph. Please use it at your own risk.



Translated with DeepL.com (free version)
