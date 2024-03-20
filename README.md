{\rtf1\ansi\ansicpg1252\cocoartf2761
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;\f1\fnil\fcharset0 HelveticaNeue-Bold;\f2\fmodern\fcharset0 Courier;
}
{\colortbl;\red255\green255\blue255;\red219\green219\blue223;\red20\green35\blue71;\red13\green20\blue34;
}
{\*\expandedcolortbl;;\cssrgb\c88627\c88627\c89804;\cssrgb\c10196\c18824\c34902;\cssrgb\c5882\c10196\c18039;
}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa360\partightenfactor0

\f0\fs28 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 This\'a0template\'a0creates\'a0the\'a0following\'a0resources:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa60\partightenfactor0
\ls1\ilvl0\cf2 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 A\'a0VPC\'a0with\'a0a\'a0public\'a0subnet.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 An\'a0internet\'a0gateway\'a0and\'a0route\'a0table\'a0to\'a0allow\'a0internet\'a0access\'a0for\'a0the\'a0public\'a0subnet.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 A\'a0security\'a0group\'a0for\'a0the\'a0API\'a0server\'a0that\'a0allows\'a0incoming\'a0traffic\'a0on\'a0port\'a080\'a0(HTTP).\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 An\'a0IAM\'a0role\'a0and\'a0instance\'a0profile\'a0for\'a0the\'a0EC2\'a0instance\'a0with\'a0permission\'a0to\'a0describe\'a0RDS\'a0instances.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 An\'a0EC2\'a0instance\'a0for\'a0the\'a0API\'a0server\'a0with\'a0the\'a0specified\'a0script\'a0in\'a0the\'a0user\'a0data.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 A\'a0security\'a0group\'a0for\'a0the\'a0RDS\'a0database\'a0that\'a0allows\'a0incoming\'a0traffic\'a0on\'a0port\'a03306\'a0(MySQL)\'a0from\'a0the\'a0API\'a0server\'a0security\'a0group.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 An\'a0RDS\'a0database\'a0instance\'a0with\'a0the\'a0specified\'a0configuration.\cb1 \
\pard\pardeftab720\sa360\partightenfactor0

\f1\b \cf2 \cb3 Please\'a0note:
\f0\b0 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa60\partightenfactor0
\ls2\ilvl0\cf2 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 You\'a0need\'a0to\'a0replace\'a0the\'a0script\'a0in\'a0the\'a0user\'a0data\'a0section\'a0with\'a0your\'a0actual\'a0script\'a0from\'a0GitHub.\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 You\'a0may\'a0need\'a0to\'a0adjust\'a0the\'a0AMI\'a0ID\'a0and\'a0RDS\'a0engine\'a0version\'a0based\'a0on\'a0your\'a0specific\'a0needs.\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Make\'a0sure\'a0you\'a0update\'a0the\'a0
\f2\fs26 \cb4 MasterUserPassword
\f0\fs28 \cb3 \'a0with\'a0a\'a0strong\'a0password.\cb1 \
\pard\pardeftab720\partightenfactor0
\cf2 \cb3 \strokec2 This\'a0template\'a0provides\'a0a\'a0basic\'a0starting\'a0point\'a0for\'a0your\'a0infrastructure.\'a0You\'a0can\'a0customize\'a0it\'a0further\'a0based\'a0on\'a0your\'a0specific\'a0requirements.\
}