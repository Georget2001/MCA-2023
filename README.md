# Week 1

### Task 1

> Identify a theme for your dataset. This will be the central, cohesive strand that will bring your data together. It can be an artist, composer, songwriter, performer, album, larger work (i.e. opera, musical, etc.), time period, genre, archival grouping, etc. You will want to be sure that you can gather all three types of data (musical scores, metadata, and audio recordings) based on your selected theme. 

For may dataset I will be choosing the 502's. The indie folk-rock group The 502's create a soundscape that captures the spirit of the heartland. Their music, which is from Maitland, Florida, seamlessly combines modern indie flair with Americana origins. The 502's encapsulate the essence of life's journey, the complexities of love, and the resiliency of the human spirit with their soulful melodies and heartfelt lyrics. Their performances elicit strong emotional responses from the audience and immerse them in the action. The 502's are a unique force in the indie music world because of their addictive energy and refreshing genuineness, which create a lasting impression on listeners. They are rooted in real storytelling.

### Task 2

>  Based on your own experience, what do you think are some challenges to working with music and music-related data (perhaps related to access, curation, distribution, etc.)? How does your selected theme display some of these challenges? Describe the current manifestations of data relating to your selected theme, discussing how it is presently curated (collected and gathered) and how it is presented, described, and analysed.


**Data Fragmentation:** Data fragmentation is a result of the fact that music-related data is frequently available across a range of platforms, databases, and formats. This makes it difficult to have a complete and centralised dataset for analysis. There are several ways that independent musicians, record labels, and streaming platforms store and share data.

**Copyright and Licencing Issues:** Because of copyright and licencing issues, accessing and utilising music data for analysis can be challenging. Since the music industry is so heavily regulated, it might be difficult to get the licences needed in order to utilise and analyse particular datasets.

**Data Quality:** For analysis to be meaningful, data connected to music must be accurate and of high quality. Research efforts might be hampered and findings misled by incomplete or erroneous metadata, mislabeled tracks, and inconsistent data entry procedures.

**Privacy Concerns:** Personal information about musicians or users may be included in certain databases pertaining to music. It can be difficult to preserve privacy while still getting insightful information, particularly when using data from social media or streaming services.

**Quick Technical Changes:** As a result of the music industry's ongoing technical development, data collection, distribution, and consumption are all impacted. It is imperative for researchers and analysts to stay abreast of these developments in order to modify their approaches and remain pertinent.

Regarding the current types of music-related data, numerous platforms such as Spotify, Apple Music, and YouTube offer enormous volumes of data regarding user preferences, streaming numbers, and playlist placements. Social media sites provide information about the involvement and popularity of an artist. Integrating data from these various sources and guaranteeing its relevance and accuracy, however, continue to be difficult tasks.

To make sense of massive datasets, forecast trends, comprehend user behaviour, and inform marketing plans, researchers and analysts frequently employ sophisticated data analytics and machine learning approaches. But managing the intricacies of music-related data—including moral and legal issues—remains a dynamic and developing topic.

# Week 2

### Task 1 

>To complete this week’s activity, you will need to accomplish the following tasks:

> 1. Identify a piece of music to download and edit.
> 2. As you did on Tuesday, download the PDF and then convert it to MuseScore
> 3. Edit at least 10 bars in MuseScore.
> 4. Discuss the aspects of your score that were not transcribed properly by the OMR engine, referencing your group discussions on Tuesday as well.

![alt text](MuseScorePiano.pdf)

![alt text](MuseScorePiano.mp3)

I thought that muse score was very effective for this piece of music. This is because it provided me with a cery accurate outcome to the original. The only areas it got confused where on the pieces that where a bit smudged or the writing wasn't too clear.  


# Week 3

### Task 1 - Generating MusicXML and MEI files


<?xml version="1.0" encoding="UTF-8"?>
<?xml-model href="https://music-encoding.org/schema/5.0/mei-all.rng" type="application/xml" schematypens="http://relaxng.org/ns/structure/1.0"?>
<?xml-model href="https://music-encoding.org/schema/5.0/mei-all.rng" type="application/xml" schematypens="http://purl.oclc.org/dsdl/schematron"?>
<mei xmlns="http://www.music-encoding.org/ns/mei" meiversion="5.0">
   <meiHead xml:id="m14kf50y">
      <fileDesc xml:id="fj9470i">
         <titleStmt xml:id="t1vfen0w">
            <title />
            <respStmt />
         </titleStmt>
         <pubStmt xml:id="p1j2gcwc">
            <date isodate="2023-12-04" type="encoding-date">2023-12-04</date>
         </pubStmt>
      </fileDesc>
      <encodingDesc xml:id="e1a3c5rn">
         <appInfo xml:id="a1j1cxs6">
            <application xml:id="a11gfmme" isodate="2023-12-04T13:24:33" version="4.0.1-a99660b">
               <name xml:id="n1ktrx89">Verovio</name>
               <p xml:id="p14aiktu">Transcoded from MusicXML</p>
            </application>
         </appInfo>
      </encodingDesc>
   </meiHead>
   <music>
      <body>
         <mdiv xml:id="m1fk9kxg">
            <score xml:id="s2v4s7d">
               <scoreDef xml:id="s107i6a">
                  <staffGrp xml:id="s190qayq">
                     <staffGrp xml:id="P1" bar.thru="true">
                        <grpSym xml:id="g14ss3lo" symbol="brace" />
                        <label xml:id="lb48vjh">Piano</label>
                        <instrDef xml:id="i1eyckfr" midi.channel="0" midi.instrnum="0" midi.volume="77.00%" />
                        <staffDef xml:id="s10y44zv" n="1" lines="5" ppq="1">
                           <clef xml:id="c3fw9hf" shape="G" line="2" />
                           <keySig xml:id="k1j5wxm4" sig="0" />
                           <meterSig xml:id="mjkqrta" count="3" unit="4" />
                        </staffDef>
                        <staffDef xml:id="snw6u9o" n="2" lines="5" ppq="1">
                           <clef xml:id="c1xe2m09" shape="F" line="4" />
                           <keySig xml:id="k18i9j4o" sig="0" />
                           <meterSig xml:id="mplrk7j" count="3" unit="4" />
                        </staffDef>
                     </staffGrp>
                  </staffGrp>
               </scoreDef>
               <section xml:id="s1hhfl1d">
                  <pb xml:id="p142vej8" />
                  <measure xml:id="m1ppxs7a" n="1">
                     <staff xml:id="skfvhvf" n="1">
                        <layer xml:id="l125zjg" n="1">
                           <note xml:id="n1o19few" dur.ppq="2" dur="2" oct="4" pname="a" stem.dir="up" />
                           <note xml:id="n16k2a1c" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="sqgigyw" n="2">
                        <layer xml:id="lhqswmi" n="5">
                           <mRest xml:id="m1aq1bsz" />
                        </layer>
                     </staff>
                     <dynam xml:id="d15x8pwn" place="below" staff="1" tstamp="1.000000" val="50" vgrp="2000">p</dynam>
                     <slur xml:id="s12p67t4" startid="#n1o19few" endid="#niom6w7" curvedir="above" />
                  </measure>
                  <measure xml:id="m4ps3z3" n="2">
                     <staff xml:id="sgvw35s" n="1">
                        <layer xml:id="lob0w59" n="1">
                           <note xml:id="n1e3rre7" dots="1" dur.ppq="3" dur="2" oct="5" pname="c" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="s1tqbm2y" n="2">
                        <layer xml:id="l1wzjr89" n="5">
                           <note xml:id="n1oypgbc" dur.ppq="2" dur="2" oct="3" pname="e" stem.dir="down" />
                           <note xml:id="n1gy3v61" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="ah5j6m8" accid="s" />
                           </note>
                        </layer>
                     </staff>
                     <slur xml:id="s13elqzc" startid="#n1oypgbc" endid="#n17x6gib" curvedir="above" />
                  </measure>
                  <measure xml:id="m17niqtt" n="3">
                     <staff xml:id="s4j6n2c" n="1">
                        <layer xml:id="l1trtgsp" n="1">
                           <note xml:id="n160f110" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                           <note xml:id="n1r2e0sg" dur.ppq="1" dur="4" oct="4" pname="a" stem.dir="up" />
                           <note xml:id="nqoqcxe" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="so3bdjl" n="2">
                        <layer xml:id="le9mehr" n="5">
                           <note xml:id="n15aup75" dots="1" dur.ppq="3" dur="2" oct="3" pname="g" stem.dir="down">
                              <accid xml:id="a1xcvur5" accid="s" />
                           </note>
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="m15tye3h" n="4">
                     <staff xml:id="s15il0ec" n="1">
                        <layer xml:id="l11ax80w" n="1">
                           <note xml:id="niom6w7" dur.ppq="1" dur="4" oct="5" pname="c" stem.dir="down" />
                           <rest xml:id="r16pcn46" dur.ppq="1" dur="4" />
                           <rest xml:id="r1n7i6x" dur.ppq="1" dur="4" />
                        </layer>
                     </staff>
                     <staff xml:id="sia81ae" n="2">
                        <layer xml:id="l1u1g2cf" n="5">
                           <note xml:id="n1duecvr" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                           <note xml:id="n6j35wm" dur.ppq="1" dur="4" oct="3" pname="b" stem.dir="down" />
                           <note xml:id="n17x6gib" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="m15jhu6v" n="5">
                     <staff xml:id="s14tsnml" n="1">
                        <layer xml:id="lqvxzat" n="1">
                           <note xml:id="nq4z48e" dur.ppq="2" dur="2" oct="4" pname="a" stem.dir="up" />
                           <note xml:id="n1sjwi46" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="sufmdmn" n="2">
                        <layer xml:id="l1e0c702" n="5">
                           <mRest xml:id="mm2f2fy" />
                        </layer>
                     </staff>
                     <slur xml:id="sd8izax" startid="#nq4z48e" endid="#nay7uov" curvedir="above" />
                  </measure>
                  <measure xml:id="mevy2uf" n="6">
                     <staff xml:id="sq4i91e" n="1">
                        <layer xml:id="l160nz13" n="1">
                           <note xml:id="n8k7m0c" dots="1" dur.ppq="3" dur="2" oct="5" pname="c" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="s1ou9zh2" n="2">
                        <layer xml:id="lbhu88t" n="5">
                           <note xml:id="n36bpdq" dur.ppq="2" dur="2" oct="3" pname="e" stem.dir="down" />
                           <note xml:id="n1g263oy" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down" />
                        </layer>
                     </staff>
                     <slur xml:id="sios7da" startid="#n36bpdq" endid="#n1gfuv7d" curvedir="above" />
                  </measure>
                  <measure xml:id="mycz8jn" n="7">
                     <staff xml:id="s1b0v0ic" n="1">
                        <layer xml:id="l1exekf1" n="1">
                           <note xml:id="n4nqljj" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                           <note xml:id="n1j6e3f3" dur.ppq="1" dur="4" oct="4" pname="a" stem.dir="up" />
                           <note xml:id="n16o06vw" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="sw3bisf" n="2">
                        <layer xml:id="l9jwreb" n="5">
                           <note xml:id="n1j43djh" dots="1" dur.ppq="3" dur="2" oct="3" pname="g" stem.dir="down">
                              <accid xml:id="a1uz2oyi" accid="s" />
                           </note>
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="mp5qfo4" n="8">
                     <staff xml:id="s15v6mug" n="1">
                        <layer xml:id="l18650y9" n="1">
                           <note xml:id="nay7uov" dur.ppq="1" dur="4" oct="5" pname="c" stem.dir="down" />
                           <rest xml:id="r19xoom9" dur.ppq="1" dur="4" />
                           <rest xml:id="r10h0j82" dur.ppq="1" dur="4" />
                        </layer>
                     </staff>
                     <staff xml:id="s109qz8f" n="2">
                        <layer xml:id="l113uys2" n="5">
                           <note xml:id="ngda4ew" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                           <note xml:id="n11li574" dur.ppq="1" dur="4" oct="3" pname="b" stem.dir="down" />
                           <note xml:id="n1gfuv7d" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                        </layer>
                     </staff>
                  </measure>
                  <sb xml:id="s1g3bp8" />
                  <measure xml:id="mkxomil" n="9">
                     <staff xml:id="sad0xwm" n="1">
                        <layer xml:id="lo05p6c" n="1">
                           <note xml:id="n14hvtuv" dur.ppq="2" dur="2" oct="5" pname="c" stem.dir="down" />
                           <note xml:id="nizd6vt" dur.ppq="1" dur="4" oct="5" pname="d" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="s1020dnv" n="2">
                        <layer xml:id="lb6rd4d" n="5">
                           <mRest xml:id="m1bgyogr" />
                        </layer>
                     </staff>
                     <slur xml:id="s192bzzs" startid="#n14hvtuv" endid="#nrmx7o8" curvedir="above" />
                  </measure>
                  <measure xml:id="m1lr0cx4" n="10">
                     <staff xml:id="s1igdy73" n="1">
                        <layer xml:id="l1yvt8pm" n="1">
                           <note xml:id="n132k5p" dur.ppq="1" dur="4" oct="5" pname="e" stem.dir="down" />
                           <note xml:id="n1vgqpq4" dur.ppq="1" dur="4" oct="5" pname="d" stem.dir="down" />
                           <note xml:id="nhnnp9q" dur.ppq="1" dur="4" oct="5" pname="c" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="s1dhyn34" n="2">
                        <layer xml:id="l1yjkfhh" n="5">
                           <note xml:id="n1b5hxy5" dur.ppq="2" dur="2" oct="3" pname="e" stem.dir="down" />
                           <note xml:id="num74ku" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="a1snn866" accid="s" />
                           </note>
                        </layer>
                     </staff>
                     <slur xml:id="s1ttehg1" startid="#n1b5hxy5" endid="#n1almbo9" curvedir="above" />
                  </measure>
                  <measure xml:id="mg3lmhb" n="11">
                     <staff xml:id="s6l0hv2" n="1">
                        <layer xml:id="lrubfha" n="1">
                           <note xml:id="n11pxdn7" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                           <note xml:id="n12pbw3i" dur.ppq="1" dur="4" oct="4" pname="a" stem.dir="up" />
                           <note xml:id="n136zchx" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="s1wohwrt" n="2">
                        <layer xml:id="l1bc67dc" n="5">
                           <note xml:id="nvcfzvf" dots="1" dur.ppq="3" dur="2" oct="3" pname="g" stem.dir="down">
                              <accid xml:id="a1jd0ugo" accid="s" />
                           </note>
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="m1ilfe00" n="12">
                     <staff xml:id="s12f614m" n="1">
                        <layer xml:id="ld8h5om" n="1">
                           <note xml:id="nrmx7o8" dots="1" dur.ppq="3" dur="2" oct="5" pname="c" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="s15qtlv4" n="2">
                        <layer xml:id="l1tne4q9" n="5">
                           <note xml:id="n1dos3qh" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                           <note xml:id="nwtl3d7" dur.ppq="1" dur="4" oct="3" pname="b" stem.dir="down" />
                           <note xml:id="nj3d4bt" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="mhavc7g" n="13">
                     <staff xml:id="scvkk2d" n="1">
                        <layer xml:id="lh4tyzk" n="1">
                           <note xml:id="nvee43m" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                           <note xml:id="n1lyiiv4" dur.ppq="1" dur="4" oct="4" pname="a" stem.dir="up" />
                           <note xml:id="n6d2w2i" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="s1xo8y3o" n="2">
                        <layer xml:id="lkcjdxw" n="5">
                           <note xml:id="n1almbo9" dur.ppq="1" dur="4" oct="3" pname="g" stem.dir="down">
                              <accid xml:id="aq8dtdi" accid="s" />
                           </note>
                           <rest xml:id="ro3ghm" dur.ppq="1" dur="4" />
                           <rest xml:id="r1xtzfky" dur.ppq="1" dur="4" />
                        </layer>
                     </staff>
                     <slur xml:id="s1wswxkv" startid="#nvee43m" endid="#n1lyiiv4" curvedir="above" />
                     <slur xml:id="s1ymt092" startid="#n1lyiiv4" endid="#n1gyid6h" curvedir="above" />
                  </measure>
                  <measure xml:id="m1m9ekvs" n="14">
                     <staff xml:id="s5mxi36" n="1">
                        <layer xml:id="ln2ibix" n="1">
                           <note xml:id="n1gyid6h" dots="1" dur.ppq="3" dur="2" oct="5" pname="c" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="sqlz9xp" n="2">
                        <layer xml:id="ltrer48" n="5">
                           <note xml:id="n1t835sb" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                           <note xml:id="n17r1ofm" dur.ppq="1" dur="4" oct="3" pname="g" stem.dir="down">
                              <accid xml:id="ac23bby" accid="s" />
                           </note>
                           <note xml:id="n15uvsv6" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="a1mxtned" accid="s" />
                           </note>
                        </layer>
                     </staff>
                     <slur xml:id="s8oittz" startid="#n1t835sb" endid="#n1d1v2nq" curvedir="above" />
                  </measure>
                  <measure xml:id="mhbjlsn" n="15">
                     <staff xml:id="s17wr0gp" n="1">
                        <layer xml:id="l1xsza7o" n="1">
                           <note xml:id="npdmlwh" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                           <note xml:id="np3p4vz" dur.ppq="1" dur="4" oct="5" pname="c" stem.dir="down" />
                           <note xml:id="nkdsg25" dur.ppq="1" dur="4" oct="4" pname="b" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="sgermaj" n="2">
                        <layer xml:id="l10pcyo4" n="5">
                           <note xml:id="n1yvqrp8" dots="1" dur.ppq="3" dur="2" oct="3" pname="g" stem.dir="down">
                              <accid xml:id="aj7b5s7" accid="s" />
                           </note>
                        </layer>
                     </staff>
                     <slur xml:id="s16ssqt5" startid="#npdmlwh" endid="#n63dl37" curvedir="above" />
                  </measure>
                  <measure xml:id="mmmffjx" right="end" n="16">
                     <staff xml:id="s5im22q" n="1">
                        <layer xml:id="l19t4iw4" n="1">
                           <note xml:id="n63dl37" dur.ppq="1" dur="4" oct="4" pname="a" stem.dir="up" />
                           <rest xml:id="rj27xxg" dur.ppq="1" dur="4" />
                           <rest xml:id="r14ompns" dur.ppq="1" dur="4" />
                        </layer>
                     </staff>
                     <staff xml:id="sut288y" n="2">
                        <layer xml:id="l1n97tr4" n="5">
                           <note xml:id="n1d1v2nq" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                           <rest xml:id="rb0lb5b" dur.ppq="1" dur="4" />
                           <rest xml:id="r3roc0h" dur.ppq="1" dur="4" />
                        </layer>
                     </staff>
                  </measure>
                  <sb xml:id="sogtc7c" />
                  <scoreDef xml:id="s1ucngi4">
                     <meterSig xml:id="m1p5njm8" count="4" unit="4" />
                  </scoreDef>
                  <measure xml:id="m30py9a" n="17">
                     <staff xml:id="s1onh4z3" n="1">
                        <layer xml:id="la1nu4n" n="1">
                           <note xml:id="n1apj7si" dots="1" dur.ppq="3" dur="2" oct="4" pname="a" stem.dir="up" />
                           <note xml:id="n35ps4m" dur.ppq="1" dur="4" oct="4" pname="g" stem.dir="up" />
                        </layer>
                     </staff>
                     <staff xml:id="slfyu35" n="2">
                        <layer xml:id="l1vr94fz" n="5">
                           <mRest xml:id="m1lez3t9" />
                        </layer>
                     </staff>
                     <slur xml:id="s1tw0amc" startid="#n1apj7si" endid="#n1lbl8tb" curvedir="above" />
                  </measure>
                  <measure xml:id="m1o7dqi2" n="18">
                     <staff xml:id="stcryfq" n="1">
                        <layer xml:id="l5lwr45" n="1">
                           <note xml:id="n13cjzj5" dots="1" dur.ppq="3" dur="2" oct="4" pname="f" stem.dir="up">
                              <accid xml:id="a1b8nx5g" accid="s" />
                           </note>
                           <note xml:id="nxpg7wl" dur.ppq="1" dur="4" oct="4" pname="e" stem.dir="up" />
                        </layer>
                     </staff>
                     <staff xml:id="s1vmgx2k" n="2">
                        <layer xml:id="l1hwyk1t" n="5">
                           <note xml:id="n1y1izqw" dur.ppq="2" dur="2" oct="3" pname="a" stem.dir="down" />
                           <note xml:id="n16gvwz0" dur.ppq="1" dur="4" oct="3" pname="g" stem.dir="down" />
                           <space xml:id="s9taq4d" dur.ppq="1" dur="4" />
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="m10w4wka" n="19">
                     <staff xml:id="syi6ofw" n="1">
                        <layer xml:id="lzylsqb" n="1">
                           <note xml:id="nwaiuyg" dots="1" dur.ppq="3" dur="2" oct="4" pname="d" stem.dir="up" />
                           <note xml:id="nhuovp6" dur.ppq="1" dur="4" oct="4" pname="e" stem.dir="up" />
                        </layer>
                     </staff>
                     <staff xml:id="s14r2ekf" n="2">
                        <layer xml:id="l8kx348" n="5">
                           <note xml:id="n9em38" dots="1" dur.ppq="3" dur="2" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="a1fjhko0" accid="s" />
                           </note>
                           <note xml:id="n12i3sbi" dur.ppq="1" dur="4" oct="3" pname="e" stem.dir="down" />
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="m7z2tao" n="20">
                     <staff xml:id="s1mxtuvq" n="1">
                        <layer xml:id="lcz8485" n="1">
                           <note xml:id="nxeygs9" dur.ppq="2" dur="2" oct="4" pname="f" stem.dir="up">
                              <accid xml:id="a6gcwlw" accid="s" />
                           </note>
                           <note xml:id="n2c4org" dur.ppq="1" dur="4" oct="4" pname="e" stem.dir="up" />
                           <note xml:id="n1lbl8tb" dur.ppq="1" dur="4" oct="4" pname="d" stem.dir="up" />
                        </layer>
                     </staff>
                     <staff xml:id="sxgrljg" n="2">
                        <layer xml:id="lzefgk" n="5">
                           <note xml:id="n1ntd56t" dur.ppq="2" dur="2" oct="3" pname="d" stem.dir="down" />
                           <note xml:id="n1ejzflp" dur.ppq="1" dur="4" oct="3" pname="e" stem.dir="down" />
                           <note xml:id="ndqg9sm" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="a1xha2eh" accid="s" />
                           </note>
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="mwkkhxi" n="21">
                     <staff xml:id="s1bfgc7a" n="1">
                        <layer xml:id="l1efjj63" n="1">
                           <note xml:id="n10k7he7" dots="1" dur.ppq="3" dur="2" oct="4" pname="e" stem.dir="up" />
                           <note xml:id="ny5wfxh" dur.ppq="1" dur="4" oct="4" pname="f" stem.dir="up">
                              <accid xml:id="axy7hop" accid="s" />
                           </note>
                        </layer>
                     </staff>
                     <staff xml:id="s1duaw7g" n="2">
                        <layer xml:id="lwy4mig" n="5">
                           <note xml:id="n15yca6n" dots="1" dur.ppq="3" dur="2" oct="3" pname="g" stem.dir="down" />
                           <note xml:id="n1wk9hfo" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="axj1cnl" accid="s" />
                           </note>
                        </layer>
                     </staff>
                     <tie xml:id="t12ch3vs" startid="#n10k7he7" endid="#nvb0sv8" />
                     <tie xml:id="t19agpaa" startid="#n15yca6n" endid="#n1tv2ih1" />
                  </measure>
                  <measure xml:id="mxp2q60" n="22">
                     <staff xml:id="s1ffipsu" n="1">
                        <layer xml:id="l1z0vot0" n="1">
                           <note xml:id="n135ccrq" dur.ppq="2" dur="2" oct="4" pname="g" stem.dir="up" />
                           <note xml:id="n640pc9" dur.ppq="1" dur="4" oct="4" pname="f" stem.dir="up">
                              <accid xml:id="a1n1z1cu" accid="s" />
                           </note>
                           <note xml:id="nvb0sv8" dur.ppq="1" dur="4" oct="4" pname="e" stem.dir="up" />
                        </layer>
                     </staff>
                     <staff xml:id="sw9oqk8" n="2">
                        <layer xml:id="l1fiff1t" n="5">
                           <note xml:id="n1s9om84" dur.ppq="2" dur="2" oct="3" pname="e" stem.dir="down" />
                           <note xml:id="no8zj60" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="a5t5c7x" accid="s" />
                           </note>
                           <note xml:id="n1tv2ih1" dur.ppq="1" dur="4" oct="3" pname="g" stem.dir="down" />
                        </layer>
                     </staff>
                     <slur xml:id="shc19qj" startid="#n1tv2ih1" endid="#nbxsy67" curvedir="below" />
                  </measure>
                  <measure xml:id="mlv9po5" n="23">
                     <staff xml:id="shr1iyj" n="1">
                        <layer xml:id="l1up7rgf" n="1">
                           <note xml:id="njly5ar" dur.ppq="1" dur="4" oct="4" pname="f" stem.dir="up">
                              <accid xml:id="a1f3uiz2" accid="s" />
                           </note>
                           <note xml:id="n1yupdjv" dur.ppq="1" dur="4" oct="4" pname="g" stem.dir="up" />
                           <note xml:id="n1del5vs" dur.ppq="1" dur="4" oct="4" pname="a" stem.dir="up">
                              <artic xml:id="a1t9hhj3" artic="stacc" />
                           </note>
                           <space xml:id="ssid0nq" dur.ppq="1" dur="4" />
                           <clef xml:id="c1j87mdi" shape="F" line="4" />
                        </layer>
                     </staff>
                     <staff xml:id="s1435qu7" n="2">
                        <layer xml:id="lop9omw" n="5">
                           <note xml:id="nbxsy67" dots="1" dur.ppq="3" dur="2" oct="3" pname="a" stem.dir="down" />
                           <note xml:id="n1lus034" dur.ppq="1" dur="4" oct="3" pname="g" stem.dir="down" />
                        </layer>
                     </staff>
                     <slur xml:id="s1esgnj9" startid="#njly5ar" endid="#n1del5vs" curvedir="below" />
                     <tie xml:id="t2ufn3p" startid="#nbxsy67" endid="#n1rhr45h" />
                  </measure>
                  <measure xml:id="m1nj0lx6" n="24">
                     <staff xml:id="seags4z" n="1">
                        <layer xml:id="l1lkpf4i" n="1">
                           <mRest xml:id="mwp8hmv" />
                           <clef xml:id="c7nerx3" shape="G" line="2" />
                        </layer>
                     </staff>
                     <staff xml:id="s1a5h4ls" n="2">
                        <layer xml:id="l1sdxv4w" n="5">
                           <note xml:id="nhvocb" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="au6n2hy" accid="s" />
                           </note>
                           <note xml:id="n1aldydh" dur.ppq="1" dur="4" oct="3" pname="g" stem.dir="down" />
                           <note xml:id="n1rhr45h" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                           <rest xml:id="r10yevk3" dur.ppq="1" dur="4" />
                        </layer>
                     </staff>
                  </measure>
                  <sb xml:id="s3rae24" />
                  <measure xml:id="my9tbpr" n="25">
                     <staff xml:id="s1akddgl" n="1">
                        <layer xml:id="lyk12py" n="1">
                           <note xml:id="n1qjdw9q" dots="1" dur.ppq="3" dur="2" oct="4" pname="a" stem.dir="up" />
                           <note xml:id="nl4voo4" dur.ppq="1" dur="4" oct="4" pname="g" stem.dir="up" />
                        </layer>
                     </staff>
                     <staff xml:id="swdanbl" n="2">
                        <layer xml:id="lrtkbqq" n="5">
                           <mRest xml:id="m1b3kbbc" />
                        </layer>
                     </staff>
                     <slur xml:id="s15ojw95" startid="#n1qjdw9q" endid="#n1kg710c" curvedir="above" />
                  </measure>
                  <measure xml:id="mbsfg31" n="26">
                     <staff xml:id="s2hiddx" n="1">
                        <layer xml:id="l1htptwx" n="1">
                           <note xml:id="n1rxzt1n" dots="1" dur.ppq="3" dur="2" oct="4" pname="f" stem.dir="up">
                              <accid xml:id="a2fsgv3" accid="s" />
                           </note>
                           <note xml:id="n1efufej" dur.ppq="1" dur="4" oct="4" pname="e" stem.dir="up" />
                        </layer>
                     </staff>
                     <staff xml:id="s1a0mi7a" n="2">
                        <layer xml:id="l1b1v5ot" n="5">
                           <note xml:id="n1rulpew" dots="1" dur.ppq="3" dur="2" oct="3" pname="a" stem.dir="down" />
                           <note xml:id="n1phyw6u" dur.ppq="1" dur="4" oct="3" pname="g" stem.dir="down" />
                        </layer>
                     </staff>
                     <pedal xml:id="p1gp4mcc" staff="2" tstamp="1.000000" dir="down" place="below" vgrp="2000" />
                     <slur xml:id="scrnkro" startid="#n1rulpew" endid="#n1bohhwt" curvedir="above" />
                  </measure>
                  <measure xml:id="mt7ewtp" n="27">
                     <staff xml:id="s1d66k" n="1">
                        <layer xml:id="l1djktdw" n="1">
                           <note xml:id="nel57sm" dots="1" dur.ppq="3" dur="2" oct="4" pname="d" stem.dir="up" />
                           <note xml:id="n1m85811" dur.ppq="1" dur="4" oct="4" pname="e" stem.dir="up" />
                        </layer>
                     </staff>
                     <staff xml:id="s16sonqt" n="2">
                        <layer xml:id="l15q9qku" n="5">
                           <note xml:id="n1qwjv7s" dots="1" dur.ppq="3" dur="2" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="a1yom156" accid="s" />
                           </note>
                           <note xml:id="n1amkcin" dur.ppq="1" dur="4" oct="3" pname="e" stem.dir="down" />
                        </layer>
                     </staff>
                     <pedal xml:id="p3ffee1" staff="2" tstamp="4.000000" dir="down" place="below" vgrp="2000" />
                  </measure>
                  <measure xml:id="mu0zwwu" n="28">
                     <staff xml:id="swtu0ir" n="1">
                        <layer xml:id="l9xsjcc" n="1">
                           <note xml:id="nv1kace" dur.ppq="2" dur="2" oct="4" pname="f" stem.dir="up">
                              <accid xml:id="ahdc6kh" accid="s" />
                           </note>
                           <note xml:id="nwbxw5q" dur.ppq="1" dur="4" oct="4" pname="e" stem.dir="up" />
                           <note xml:id="n1kg710c" dur.ppq="1" dur="4" oct="4" pname="d" stem.dir="up" />
                        </layer>
                     </staff>
                     <staff xml:id="s1esv2u5" n="2">
                        <layer xml:id="liht3zr" n="5">
                           <note xml:id="nba2tl4" dur.ppq="2" dur="2" oct="3" pname="d" stem.dir="down" />
                           <note xml:id="napq6s0" dur.ppq="1" dur="4" oct="3" pname="e" stem.dir="down" />
                           <note xml:id="n1bohhwt" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="a8cyw6b" accid="s" />
                           </note>
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="m2tld4z" n="29">
                     <staff xml:id="s1i00xew" n="1">
                        <layer xml:id="loip784" n="1">
                           <note xml:id="n605rji" dots="1" dur.ppq="3" dur="2" oct="4" pname="e" stem.dir="up" />
                           <note xml:id="npk8u98" dur.ppq="1" dur="4" oct="4" pname="f" stem.dir="up">
                              <accid xml:id="a1c6ekpi" accid="s" />
                           </note>
                        </layer>
                     </staff>
                     <staff xml:id="s1low6z8" n="2">
                        <layer xml:id="l1ldvamf" n="5">
                           <note xml:id="n1lrytf6" dots="1" dur.ppq="3" dur="2" oct="3" pname="g" stem.dir="down" />
                           <note xml:id="nshm4j" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="a1v8j7tx" accid="s" />
                           </note>
                        </layer>
                     </staff>
                     <tie xml:id="t1fg48b4" startid="#n605rji" endid="#n1ym3uq0" />
                     <tie xml:id="to457ao" startid="#n1lrytf6" endid="#nmmf2vf" />
                  </measure>
                  <measure xml:id="mi3mt02" n="30">
                     <staff xml:id="so3eu47" n="1">
                        <layer xml:id="lyqs34c" n="1">
                           <note xml:id="n1pxefa5" dur.ppq="2" dur="2" oct="4" pname="g" stem.dir="up" />
                           <note xml:id="nsc37ak" dur.ppq="1" dur="4" oct="4" pname="f" stem.dir="up">
                              <accid xml:id="appkhju" accid="s" />
                           </note>
                           <note xml:id="n1ym3uq0" dur.ppq="1" dur="4" oct="4" pname="e" stem.dir="up" />
                        </layer>
                     </staff>
                     <staff xml:id="s1ccm1le" n="2">
                        <layer xml:id="l15js4ca" n="5">
                           <note xml:id="n3ol338" dur.ppq="2" dur="2" oct="3" pname="e" stem.dir="down" />
                           <note xml:id="n1x028j9" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="a13y7g12" accid="s" />
                           </note>
                           <note xml:id="nmmf2vf" dur.ppq="1" dur="4" oct="3" pname="g" stem.dir="down" />
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="m1pn84u8" n="31">
                     <staff xml:id="sqpv5hy" n="1">
                        <layer xml:id="l1yqvqcb" n="1">
                           <note xml:id="nokcrql" dur.ppq="1" dur="4" oct="4" pname="f" stem.dir="up">
                              <accid xml:id="adr7tdb" accid="s" />
                           </note>
                           <note xml:id="n14xo6w9" dur.ppq="1" dur="4" oct="4" pname="e" stem.dir="up" />
                           <note xml:id="n1oqo633" dur.ppq="1" dur="4" oct="4" pname="d" stem.dir="up" />
                           <rest xml:id="rub9t2g" dur.ppq="1" dur="4" />
                        </layer>
                     </staff>
                     <staff xml:id="s1va90xm" n="2">
                        <layer xml:id="l1swig54" n="5">
                           <note xml:id="n1fkliro" dots="1" dur.ppq="3" dur="2" oct="3" pname="a" stem.dir="down" />
                           <note xml:id="n14vngxn" dur.ppq="1" dur="4" oct="3" pname="g" stem.dir="down" />
                        </layer>
                     </staff>
                     <slur xml:id="syyb33u" startid="#nokcrql" endid="#n1oqo633" curvedir="below" />
                     <slur xml:id="s181tilb" startid="#n1fkliro" endid="#nono7dr" curvedir="above" />
                  </measure>
                  <measure xml:id="mxcf14d" right="end" n="32">
                     <staff xml:id="smxolti" n="1">
                        <layer xml:id="l1n1w33q" n="1">
                           <mSpace xml:id="m1uiaqxn" />
                        </layer>
                     </staff>
                     <staff xml:id="s18rd41t" n="2">
                        <layer xml:id="l173xfw1" n="5">
                           <note xml:id="nx8bfhh" dur.ppq="1" dur="4" oct="3" pname="f" stem.dir="down">
                              <accid xml:id="a1e3t5tn" accid="s" />
                           </note>
                           <note xml:id="n1om1w5x" dur.ppq="1" dur="4" oct="3" pname="e" stem.dir="down" />
                           <note xml:id="nono7dr" dur.ppq="1" dur="4" oct="3" pname="d" stem.dir="down" />
                           <rest xml:id="r133e52c" dur.ppq="1" dur="4" />
                        </layer>
                     </staff>
                  </measure>
                  <sb xml:id="siimeav" />
                  <scoreDef xml:id="srzpuj2">
                     <meterSig xml:id="mdrbl82" count="4" unit="4" />
                  </scoreDef>
                  <measure xml:id="mk4ieyp" n="33">
                     <staff xml:id="svusux" n="1">
                        <layer xml:id="lw7248t" n="1">
                           <note xml:id="n4k3r0h" dur.ppq="4" dur="1" oct="5" pname="g" />
                        </layer>
                     </staff>
                     <staff xml:id="s1lefka1" n="2">
                        <layer xml:id="l1j0chjb" n="5">
                           <mRest xml:id="m9g3ddz" />
                        </layer>
                     </staff>
                     <dynam xml:id="d4lbc53" place="below" staff="1" tstamp="1.000000" val="90" vgrp="2000">f</dynam>
                     <slur xml:id="s12brzeg" startid="#n4k3r0h" endid="#npy5j9i" curvedir="above" />
                     <tie xml:id="t1bmamdp" startid="#n4k3r0h" endid="#n11nrr52" />
                  </measure>
                  <measure xml:id="m1smb9q8" n="34">
                     <staff xml:id="s12imihg" n="1">
                        <layer xml:id="l1hf0jdq" n="1">
                           <note xml:id="n11nrr52" dur.ppq="1" dur="4" oct="5" pname="g" stem.dir="down" />
                           <note xml:id="nykjnfw" dur.ppq="1" dur="4" oct="5" pname="f" stem.dir="down" />
                           <note xml:id="nhrlgar" dur.ppq="1" dur="4" oct="5" pname="e" stem.dir="down" />
                           <note xml:id="n1p7kpua" dur.ppq="1" dur="4" oct="5" pname="d" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="sp1pbon" n="2">
                        <layer xml:id="luet4w4" n="5">
                           <note xml:id="nwa9a6z" dur.ppq="2" dur="2" oct="3" pname="g" stem.dir="down">
                              <artic xml:id="a1n6yjnv" artic="marc" />
                           </note>
                           <note xml:id="nqlw15s" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                           <note xml:id="n1lc5glu" dur.ppq="1" dur="4" oct="3" pname="b" stem.dir="down" />
                        </layer>
                     </staff>
                     <slur xml:id="s1dp9ksa" startid="#nwa9a6z" endid="#n1lc5glu" curvedir="above" />
                  </measure>
                  <measure xml:id="mzhj9ul" n="35">
                     <staff xml:id="s1gqt4e7" n="1">
                        <layer xml:id="l1kq5x0o" n="1">
                           <note xml:id="nvdhk3y" dur.ppq="2" dur="2" oct="5" pname="e" stem.dir="down" />
                           <note xml:id="n32hcys" dur.ppq="1" dur="4" oct="5" pname="d" stem.dir="down" />
                           <note xml:id="nej8or9" dur.ppq="1" dur="4" oct="5" pname="e" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="sru266x" n="2">
                        <layer xml:id="luutmv0" n="5">
                           <note xml:id="n1g1l80k" dur.ppq="4" dur="1" oct="4" pname="c" />
                        </layer>
                     </staff>
                     <slur xml:id="sfp0le6" startid="#n1g1l80k" endid="#n1reyam" curvedir="above" />
                     <tie xml:id="t1ayyqlc" startid="#n1g1l80k" endid="#n1rvth0h" />
                  </measure>
                  <measure xml:id="m112lygl" n="36">
                     <staff xml:id="s1yb815y" n="1">
                        <layer xml:id="l184h7ef" n="1">
                           <note xml:id="npy5j9i" dur.ppq="4" dur="1" oct="5" pname="f" />
                        </layer>
                     </staff>
                     <staff xml:id="s1q9no1p" n="2">
                        <layer xml:id="lgm9rhd" n="5">
                           <note xml:id="n1rvth0h" dur.ppq="1" dur="4" oct="4" pname="c" stem.dir="down" />
                           <note xml:id="n1luu43y" dur.ppq="1" dur="4" oct="3" pname="b" stem.dir="down" />
                           <note xml:id="n1mh6ktl" dur.ppq="1" dur="4" oct="3" pname="a" stem.dir="down" />
                           <note xml:id="n1reyam" dur.ppq="1" dur="4" oct="3" pname="b" stem.dir="down" />
                        </layer>
                     </staff>
                  </measure>
                  <measure xml:id="mfi1w2z" n="37">
                     <staff xml:id="s5ehkl7" n="1">
                        <layer xml:id="l12hjig7" n="1">
                           <note xml:id="n1myb39u" dur.ppq="2" dur="2" oct="5" pname="e" stem.dir="down" />
                           <note xml:id="n7kbha7" dur.ppq="1" dur="4" oct="5" pname="d" stem.dir="down" />
                           <note xml:id="n1k3dc7s" dur.ppq="1" dur="4" oct="5" pname="e" stem.dir="down" />
                        </layer>
                     </staff>
                     <staff xml:id="s115kypp" n="2">
                        <layer xml:id="lqnb9a7" n="5">
                           <note xml:id="nreqpka" dur.ppq="4" dur="1" oct="4" pname="c">
                              <artic xml:id="ag5z41j" artic="marc" />
                           </note>
                        </layer>
                     </staff>
                  </measure>
               </section>
            </score>
         </mdiv>
      </body>
   </music>
</mei>















