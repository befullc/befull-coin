# befull-coin
BFC（BeFullCoin) is the official token of BeFull Community , the world’s largest EOS-based Chinese community. 


Why
There are over 3000 tokens on EOS mainnet (According to EOSPark Tokens).

Unfortunately, it's hard for developers to collect all the tokens' logo and other info. Thus limited the chance to provide a better user experience for users.

This lib aims to collect all the tokens and their data including their logo/precision/desc/website, etc.

Contributing
PR is welcome!

Star this repository

Create a folder under /tokens named with token's account /tokens/${CONTRACT_ACCOUNT}

Then add yor token LOGO and JSON file under the folder. /tokens/${CONTRACT_ACCOUNT}/{TOKEN_UPPERCASE}.png /tokens/${CONTRACT_ACCOUNT}/{TOKEN_UPPERCASE}.json

Create PR, and leave your contact (Telegram/WeChat/Email) in comment for further support.

Please refer to eosio.token::EOS for token example.

Feel free to submit tokens if you are the token's owner or not, the community needs your contribution :).

Thanks to Newdex, EOSPark and EOS cafe for initial data.

Template
Please submit your token's JSON file follow template below. EOS

DON'T modify tokens.json as it is auto generated.

{
  "name": "EOS",
  "symbol": "EOS",
  "contract": "eosio.token",
  "issuer": "eosio",
  "precision": 4,
  "logo": "https://raw.githubusercontent.com/BlockABC/eos-tokens/master/tokens/{CONTRACT_ACCOUNT}/{TOKEN_NAME_UPPERCASE}.png",
  "desc": {
    "en": "EOS (Enterprise Operation System) is a blockchain smart contract platform developed by Block.one, which aims to provide bottom blockchain platform services for high-performance distributed applications.",
    "zh": "EOS (Enterprise Operation System) 是一个区块链智能合约平台，由Block.one 开发。它致力于为高性能分布式应用提供区块链底层服务。",
    "ko": "EOS (Enterprise Operation System) 는 블록 스마트 플랫폼으로 블 락 원 (Block.one)이 개발 했다.고성능 분산 식 응용을 위해 지역 체인 하위 서비스를 제공 합니다."
  },
  "website": "https://eos.io",
  "whitepaper": "https://github.com/EOSIO/Documentation/blob/master/TechnicalWhitePaper.md",
  "links": {
    "github": "https://github.com/{your-token}",
    "telegram": "https://t.me/joinchat/{your-token}",
    "twitter": "https://twitter.com/{your-token}",
    "steemit": "https://steemit.com/{your-token}",
    "reddit": "https://www.reddit.com/r/{your-token}/",
    "wechat": "{your-token}"
  }
}
Note
For better compatibility, please provide PNG format as possible.
invalid field is only used to indicate that this token is invalid on chain. If your token is valid, please don't fill in this field.
Token List
Logo	Symbol	Account Name
	TOD	21dice4token
	ACC	accissuer123
	ADM	admsadmtoken
	ARN	aeronaerozzz
	EPT	alibabapoole
	BAC	alliance1111
	ANGE	angelcitytok
	ANL	angeliumseed
	ATHENA	athenastoken
	BEES	beesgamecont
	CHIP	bet24tokens1
	BCC	betcitytoken
	DICE	betdicetoken
	BET	betdividends
	BG	bgbgbgbgbgbg
	BINGO	bingobetoken
	BITI	biteyebiteye
	EBTC	bitpietokens
	EETH	bitpietokens
	LNC	bitwala.bank
	MIR	blockmirmain
	BOID	boidcomtoken
	BOX	boxgametoken
	BUFF	buff123token
	EOSISH	buildertoken
	LITE	buildertoken
	BMT	bymunitycoin
	ADE	cadeositoken
	CARMEL	carmeltokens
	CPLE	carpoolslife
	CHL	challengedac
	CHEX	chexchexchex
	LKT	chyyshayysha
	LIGHT	coinscentral
	CONST	constantteam
	MANIA	crmaniatoken
	PSO	cryptopesosc
	CRYPAY	crytonsource
	CRYTON	crytonsource
	MAIL	d.mail
	CTN	dacincubator
	YDAPP	dacincubator
	DBET	dbetminepool
	DET	diceeostoken
	DION	dioncoinmake
	EATCOIN	eatscience14
	ECTT	ectchaincoin
	EDNA	ednazztokens
	EKD	ekdtokenbank
	ET	endlesstoken
	EOSABC	eosabctokens
	ADD	eosadddddddd
	ATD	eosatidiumio
	EAP	eosauctionpt
	BONE	eosbet5token
	BLACK	eosblackteam
	BOCAI	eosbocai1111
	BOOK	eosbookchain
	MV	eosbookchain
	BT	eosbtextoken
	BTN	eosbuttonbtn
	DAB	eoscafekorea
	CAN	eoscancancan
	CANDY	eoscandymain
	CRASH	eoscrashplay
	CUBE	eoscubetoken
	EOSDAC	eosdactokens
	DRAGON	eosdragontkn
	DY	eosdyeosiody
	EDE	eosede1token
	ENB	eosenbpocket
	SVN	eoseventoken
	FAID	eosfaidchain
	FUN	eosfuntoken1
	BEST	eosgamecoin2
	GT	eosgetgtoken
	GGS	eosggshost11
	IGC	eosindiegame
	EOS	eosio.token
	CET	eosiochaince
	LOTC	eosiolotcoin
	MEETONE	eosiomeetone
	MORE	eosiomoreone
	EGT	eosiotokener
	TPT	eosiotptoken
	JKR	eosjackscoin
	JUST	eosjusttoken
	KEEP	eoskeep.x
	ERO	eoslandadmin
	LUCK	eosluckchain
	LUCKY	eoslucktoken
	MAX	eosmax1token
	EOSNTS	eosninetiess
	POKER	eospokercoin
	RAN	eosrandtoken
	ROY	eosroyaleroy
	TGC	eostgctoken1
	EOST	eostrantoken
	MEV	eosvegascoin
	EVR	eosvrtokenss
	WINS	eoswinonewww
	ZEC	eoswwwzeccom
	EOSYX	eosyxtoken11
	EOX	eoxeoxeoxeox
	EPG	epgamblertns
	EPRA	epraofficial
	ESB	esbcointoken
	EETH	ethsidechain
	EOSWIN	etwineos1111
	IQ	everipediaiq
	EWGT	eworldtoken1
	FAIR	faireostoken
	KKK	fairkuai3kkk
	FOS	farmeosbankx
	FAST	fastecoadmin
	SLIEMT	fastwinitemf
	STAR	fastwinitems
	FC	fcfundadmins
	NFT	fight22death
	FISH	fishjoytoken
	FLB	flappybirds1
	LOTT	forlot111222
	FROG	frogfrogcoin
	CITY	funcitytoken
	GMB	game12game34
	GBT	gamebettoken
	BOY	gameboytoken
	GMC	gamechaineos
	GHT	gamershypeca
	SKY	gameskytoken
	GEM	gemcitytoken
	SHAPE	gmaslaunches
	GOC	gocgocgocgoc
	LZB	gqydooigenes
	BTC	grandpacoins
	GYM	gymrewardsio
	BABY	hashbabycoin
	HBGO	hashbabycoin
	HBS	hashbabycoin
	HIG	higoldtokens
	HVT	hirevibeshvt
	ECASH	horustokenio
	HORUS	horustokenio
	HOT	hotbetstoken
	INF	infinicoinio
	POST	ipsecontract
	AGT	jychjych1234
	KEOS	keoskorea111
	YKC	lame12341235
	TEA	linzongsheng
	LGT	liveadmin123
	LLG	llgonebtotal
	LOVE	lovewintoken
	LOV	lovlovlovlov
	LT	luckbettoken
	LNT	lucknumtoken
	LKG	luckygotoken
	ROLL	luckymetoken
	LUME	lumetokenctr
	MANGO	mangotokenll
	MIR	mirchainteam
	KEY	mkstaketoken
	MOM	mothereosoo1
	MUGL	mugglesspell
	MUR	murmurtokens
	LEXIBIT	mywhaletoken
	NEB	nebulatokenn
	NDX	newdexissuer
	NTWD	newtaiwanbis
	ATMOS	novusphereio
	NUTS	nutscontract
	OBT	obtain.e
	OCT	octtothemoon
	OFS	offsidetoken
	LED	okkkkkkkkkkk
	YT	okkkkkkkkkkk
	ONE	onebosonebos
	ONE	onedicewarm2
	IPOS	oo1122334455
	BRM	openbrmeos11
	SEED	parslseed123
	PIZZA	pizzatotoken
	PLO	ploutoztoken
	PKE	pokereotoken
	POOR	poormantoken
	P	ppppp.e
	PGL	prospectorsg
	PSI	psidicetoken
	PTI	ptitokenhome
	PUB	publytoken11
	PUML	pumlhealthio
	PXS	pxstokensapp
	RAM	ramtokenmoon
	RWC	realworldcpn
	RIDL	ridlridlcoin
	FORTUNE	roulette4tok
	SAND	sandgrptoken
	SENSE	sensegenesis
	ESA	shadowbanker
	SHARE	share.x
	SST	skillshareio
	SKR	skreosxtoken
	CUSD	stablecarbon
	DOLLAR	supstartoken
	TOOK	taketooktook
	TOE	talkoneos123
	TASTE	taste.x
	BEAN	thebeantoken
	BETX	thebetxtoken
	DEOS	thedeosgames
	EFOR	theforcecoin
	EFOR	theforcegrou
	PEOS	thepeostoken
	KARMA	therealkarma
	TKC	tkcointkcoin
	TOB	tobetiotoken
	CAT	tokenbyeocat
	TOP	topdapptoken
	TBT	trustbetteam
	TXT	trusteamwins
	TRYBE	trybenetwork
	TWERK	twerkeoscoin
	UBQ	u.b.q
	UCTT	uctokenowner
	USDE	usdetotokens
	UTG	untowermain1
	GR	valvegame.m
	WECASH	weosservices
	WAL	whaleextoken
	WIN	windividends
	WIZBOX	wizboxairdro
	WIZZ	wizznetwork1
	LYNX	worktokenbvi
	WRK	worktokenbvi
	XBX	xbxtokencore
	XMC	xiaomiaocoin
	XPC	xpctokencore
	XPT	xpttokencore
	SEVEN	xxxsevensxxx
	YOU	youbaoyoubao
	YUM	yumgamescoin
	ZT	z1gametoken1
	ZION	ziongameseos
	ZKS	zkstokensr4u
	ZOS	zosionetwork
