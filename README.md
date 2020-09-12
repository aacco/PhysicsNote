# PhysicsNote

ちょっとづつ作成していきます。
共著者を探しています。思うところがあればぜひご一報ください！

## 読み方

ノートを各ディレクトリ内にPDFファイルとしてまとめてあります.
tex->dvi->pdf

## directory structure

### 注意

.gitingoreも参照:マクロや一部ファイルはcommitから排しています.

	/PhysicsNote
		.gitignore
		README.md
		
		/analytical (解析力学)

		/em (電磁気学)
			em.tex	
		
		/master (目次)
			master.tex

		/math (前提の数学概念)
			pre.tex		

		/mechanics (初等力学)
			equation_of_motion.tex
			shm.tex
		
		/others (その他)
			column.tex

		/particles　(素粒子論)

		/quantum (量子力学)

		/relativism (相対論)

		/sty (TeXのstyファイルを格納)
			macros.sty
			mymacros.sty

		/ts (熱,統計力学)
			tasaki.tex	
			th.tex
		
		



#指針に替えて

master.texを目次とし,各分野のtexファイルを個別フォルダに分けてある.
各章にはまず概論を置き,物理法則の根幹とも言える式の変遷を俯瞰した後に,(できたら)各節で詳細な説明を付してある.
これは筆者が物理学の基礎を簡潔,体系的にとらえなおすことを目的として書かれたものであるがもちろん読者のさまざまな活用法に対応した(つもりの)ものでもある.そしてこの目的のために,書式や内容は漸次改定,改善する所存である.
そのためにも多様に亘る御批判や御助言を賜るとともに,本書が読者の物理学理解の一助とならんことを願うばかりである.

的な.
