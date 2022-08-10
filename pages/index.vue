<template>
  <main>
    <div class="main-panel-out">
      <div class="main-contents">
        <h1 class="main-text">
          <span class="main-text-sub">あなたの隣に這いよるナビAIを作る</span>
          AIエンジニア
        </h1>
        <div class="main-image">
          <img src="~assets/images/index_main1.png" alt="" width="306" height="483">
        </div>
      </div>
    </div>

    <section id="why_ai">
      <div class="contents">
        <div class="contents_title">
          <h2>なぜナビゲーションAIなのか</h2>
        </div>
        <div class="contents_list">
          <div class="img_wrap">
            <img src="~assets/images/index_content1.png" alt="">
          </div>
          <div class="img_wrap">
            <img src="~assets/images/index_content2.png" alt="">
          </div>
          <div class="img_wrap">
            <img src="~assets/images/index_content3.png" alt="">
          </div>
        </div>
      </div>
    </section>

    <section id="work">
      <div class="work_contents">
        <div class="contents_title">
          <h2>AIエンジニアの仕事</h2>
        </div>

        <div class="work_contents_list">
          <div class="work_block">
            <div class="work_image">
              <img src="~assets/images/index_work1.png" alt="" width="157" height="127">
            </div>
            <div class="work_text">
              <h3>
                最新論文のリサーチ</h3>
              <h4 class="work_text_sub">日々新しい理論が出るため、論文を読み込んで実装することが必要となる。<br>最先端の研究はほぼ英語のため、英語の読解能力は必須</h4>
            </div>
          </div>

          <div class="work_block">
            <div class="work_image">
              <img src="~assets/images/index_work2.png" alt="" width="176" height="144">
            </div>
            <div class="work_text">
              <h3>
                アルゴリズム・モデル開発</h3>
              <h4 class="work_text_sub">データを与えて学習させて、対話モデルなどのAIを作る。<br>正解率を高めるために、データを増やしたりモデルの微調整を行ったりしていく。</h4>
            </div>
          </div>

          <div class="work_block">
            <div class="work_image">
              <img src="~assets/images/index_work3.png" alt="" width="129" height="119">
            </div>
            <div class="work_text">
              <h3>
                実証実験</h3>
              <h4 class="work_text_sub">試験運用を行う。モデルは想定通りの精度であるか、<br>想定外の動きがないか検証する。</h4>
            </div>
          </div>

          <div class="work_block">
            <div class="work_image">
              <img src="~assets/images/index_work4.png" alt="" width="169" height="106">
            </div>
            <div class="work_text">
              <h3>
                開発業務</h3>
              <h4 class="work_text_sub">実際のソフトウェアで使うために、学習したモデルを開発に組み込む。</h4>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="skills">
      <div class="skill_contents">
        <div class="contents_title">
          <h2>AIエンジニアの必要知識・スキル</h2>
        </div>

        <div class="skill_contents_list">
          <div class="skill_text">
            <h3>
              ソフトウェア全般</h3>
            <div class="skill_text_sub">
              <h4>
                プログラミング言語の理解、WEBアプリとして公開するならWEBサーバー周りなど情報系の知識は一通り必要。
              </h4>
            </div>
          </div>

          <div class="skill_text">
            <h3>
              統計知識・数学</h3>
            <div class="skill_text_sub">
              <h4>
                時の噂であったDeepLearning、機械学習の理解には統計知識が欠かせない。線形代数等の数学的知識も必要。
              </h4>
            </div>
          </div>

          <div class="skill_text">
            <h3>
              音声処理</h3>
            <div class="skill_text_sub">
              <h4>音声入力した言葉を認識、ノイズを取り除いたうえで分析を行う。リアルタイム性も要求されるため求められるハードルが高い</h4>
            </div>
          </div>

          <div class="skill_text">
            <h3>
              自然言語処理</h3>
            <div class="skill_text_sub">
              <h4>主語・述語を分解。今何をすることが求められているのかを把握するために必要。日本語専用のモデルを作る必要がある。</h4>
            </div>
          </div>

          <div class="skill_text">
            <h3>
              英語</h3>
            <div class="skill_text_sub">
              <h4>最新の研究結果はグローバルスタンダードである英語で書かれている。日本語に翻訳されるのを待っているわけにはいかないため、英語ですぐに読むことが大切になる。</h4>
            </div>
          </div>

          <div class="skill_text">
            <h3>
              その他</h3>
            <div class="skill_text_sub">
              <h4>ナビAIを3Dキャラクターにするのならば3Dモデリングの知識、VRやAR上で表示させるのならそれらのハードウェアについての知識も必要になってくる。</h4>
            </div>
          </div>
        </div>
      </div>

    </section>

    <section id="faq">
      <div class="faq_contents">
        <div>
          <div class="faq_title_sub">FAQ</div>
          <div class="contents_title">
            <h2>よくあるご質問</h2>
          </div>
        </div>

        <div class="faq_contents_list">
          <SlideUpDown question="Q 彼女・彼氏じゃダメなの？"
            answer="<br>全然違う！！<br>彼女・彼氏は親愛・安心感を求めるのに対して、<br>ナビAIに求めるのは効率化・友達・秘書のような役割として求める。<br>求めるものが違うため両立する。<br>夫・妻がいても推しは別にいるというイメージ" />
          <!--
          <SlideUpDown question=" Q 参考作品を教えて" answer='<br>「SAOシリーズ」から<span class="hover1">"ユイ"</span><br>「アイアンマンシリーズ」から<span
                    class="hover2">"ジャーヴィス"</span><br>「ガニメデの優しい巨人」から"ゾラック"<br>「Beatless」から<span
                    class="hover3">"レイシア"</span>等<br><br>どの作品でも人間を手助けするAI、よきコンビとして描かれている' />

          <SlideUpDown question="Q 要するに可愛いGoogleアシスタント？"
            answer="<br>考え方は似ているもの。<br>Googleアシスタントは世界中の人々に馴染んでもらうために、あえて記号的なデザインにして個性を削っていると思われる。<br>私からすると愛着が持ちづらいから、もっと個性を付けたい<br>コンテンツ力の高い日本ならそういうことは得意と考えている" />
-->
          <!--
          <div class="faq_block">
            <div class="faq_text">
              <div class="faq_text_center">
                <h3>
                  Q 彼女・彼氏じゃダメなの？</h3>
              </div>
            </div>
            <div class="faq_text_sub">
              <div class="faq_text_sub_center">
                <h4>
                  <br>全然違う！！<br>彼女・彼氏は親愛・安心感を求めるのに対して、<br>ナビAIに求めるのは効率化・友達・秘書のような役割として求める。<br>求めるものが違うため両立する。<br>夫・妻がいても推しは別にいるというイメージ
                </h4>
              </div>
            </div>
          </div>

          <div class="faq_block">
            <div class="faq_text">
              <div class="faq_text_center">
                <h3>
                  Q 参考作品を教えて</h3>
              </div>
            </div>
            <div class="faq_text_sub">
              <div class="faq_text_sub_center">
                <h4>
                  <br>「SAOシリーズ」から<span class="hover1">"ユイ"</span><br>「アイアンマンシリーズ」から<span
                    class="hover2">"ジャーヴィス"</span><br>「ガニメデの優しい巨人」から"ゾラック"<br>「Beatless」から<span
                    class="hover3">"レイシア"</span>等<br><br>どの作品でも人間を手助けするAI、よきコンビとして描かれている
                </h4>
              </div>
            </div>
          </div>

          <div class="faq_block">
            <div class="faq_text">
              <div class="faq_text_center">
                <h3>
                  Q 要するに可愛いGoogleアシスタント？
                </h3>
              </div>
            </div>
            <div class="faq_text_sub">
              <div class="faq_text_sub_center">
                <h4>
                  <br>考え方は似ているもの。<br>Googleアシスタントは世界中の人々に馴染んでもらうために、あえて記号的なデザインにして個性を削っていると思われる。<br>私からすると愛着が持ちづらいから、もっと個性を付けたい<br>コンテンツ力の高い日本ならそういうことは得意と考えている
                </h4>
              </div>
            </div>
          </div>
                  -->
        </div>
      </div>

    </section>

  </main>
</template>

<script>
import SlideUpDown from "~/components/SlideUpDown";
export default {
  components: { SlideUpDown }
}
</script>