<template>
  <div>
    <v-layout>
      <v-flex xs12 sm10>
        <v-card>
          <v-card-title class="primary white--text" primary-title>
            <v-btn dark icon @click="back">
              <v-icon>chevron_left</v-icon>
            </v-btn>
            <div>
              <h3 class="headline mb-0">{{ $t('settings.termOfService') }}</h3>
            </div>
          </v-card-title>
          <v-card-text class="desc-terms-of-service">
            <p><b><span style='font-size:12.0pt;line-height:115%'>SEN POINTプロジェクトサービス</span></b></p>

            <p><b><span style='font-size:12.0pt;line-height:115%'>利用規約</span></b></p>

            <p>&nbsp;</p>

            <p>この規約は、お客様が、株式会社ＴＴＪ（以下「当社」）が提供する「SEN POINTプロジェクト」（以下「本サービス」）をご利用頂く際の取扱いにつき定めるものです。本規約に同意した上で本サービス(<a target="_blank" href="http://www.ttjworld.com"><span
                style='color:#1155CC'>https://www.ttjworld.com</span></a> およびTTJ ウォレット）をご利用ください。</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第１条（定義）</p>

            <p>&nbsp;</p>

            <p style='margin-left:12.0pt'>本規約上で使用する用語の定義は、次に掲げるとおりとします。</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(1)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>本サービス	当社が運営するサービス及び関連するサービス</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(2)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>本サイト	本サービスのコンテンツが掲載されたウェブサイト</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(3)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>本コンテンツ	本サービス上で提供されるウォレットプログラム、コード、文字、静止画、動画等の総称  </p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(4)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>利用者	  本サービスを利用する全ての方</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(5)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>登録利用者	 本サイトの利用者登録が完了した方</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(6)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>メールアドレス	 本サービスの利用のために登録利用者が固有に持つ文字列</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(7)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>パスワード	 ＩＤに対応して登録利用者が固有に設定する暗号</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(8)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>個人情報	住所、氏名、職業、電話番号、生年月日等個人を特定することのできる情報の総称</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(9)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>登録情報	登録利用者が本サイトにて登録した情報の総称</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第２条（本規約への同意）</p>

            <p>&nbsp;</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>1<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>利用者は、本利用規約に同意頂いた上で、本サービスを利用できるものとします。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>2<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>利用者が、本サービスをスマートフォン等その他情報端末にダウンロードし、本規約への同意手続を行った時点で、利用者と当社との間で、本規約の諸規定に従った利用契約が成立するものとします。<p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>3<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>利用者が未成年者である場合には、親権者その他の法定代理人の同意を得たうえで、本サービスをご利用ください。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>4<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>未成年者の利用者が、法定代理人の同意がないにもかかわらず同意があると偽りまたは年齢について成年と偽って本サービスを利用した場合、その他行為能力者であることを信じさせるために詐術を用いた場合、本サービスに関する一切の法律行為を取り消すことは出来ません。<p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>5<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>本規約の同意時に未成年であった利用者が成年に達した後に本サービスを利用した場合、当該利用者は本サービスに関する一切の法律行為を追認したものとみなされます。</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第３条（規約の変更）</p>

            <p>&nbsp;</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>1<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社は、利用者の承諾を得ることなく、いつでも、本規約の内容を改定することができるものとし、利用者はこれを異議なく承諾するものとします。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>2<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社は、本規約を改定するときは、その内容について当社所定の方法により利用者に通知します。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>3<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>前本規約の改定の効力は、当社が前項により通知を行った時点から生じるものとします。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>4<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>利用者は、本規約変更後、本サービスを利用した時点で、変更後の本利用規約に異議なく同意したものとみなされます。</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第４条（会員の登録手続）</p>

            <p>&nbsp;</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>1<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>本サービスへの登録を希望する方（以下「登録希望者」）は、本規約に同意した上で、所定の方法で登録を行ってください。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>2<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>登録をした方は、弊社がその登録を承諾し、ＩＤ登録が完了した時点から登録ユーザとなります。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>3<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>弊社は、登録ユーザ向けにメールで連絡事項の告知や広告その他の情報提供を行います。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>4<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>弊社は、登録希望者が次の各号のいずれか一つに該当する場合は、弊社の判断により登録を承諾しないことがあります。</p>

            <p style='margin-left:42.0pt;text-indent:-18.0pt'>一<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>登録希望者が、弊社の定める方法によらず登録を行った場合 </p>

            <p style='margin-left:42.0pt;text-indent:-18.0pt'>二<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>登録希望者が、過去に本規約または弊社の定めるその他の利用規約等に違反したことを理由として退会処分を受けた者である場合</p>

            <p style='margin-left:42.0pt;text-indent:-18.0pt'>三<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>登録希望者が、不正な手段をもって登録を行っていると弊社が判断した場合</p>

            <p style='margin-left:42.0pt;text-indent:-18.0pt'>四<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>登録希望者が、本人以外の情報を登録している場合</p>

            <p style='margin-left:42.0pt;text-indent:-18.0pt'>五<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>その他弊社が不適切と判断した場合</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第５条（アカウントの管理）</p>

            <p>&nbsp;</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>1<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>利用者は、利用に際して登録した情報（以下、「登録情報」といいます。メールアドレスやパスワード等を含みます）について、自己の責任の下、任意に登録、管理するものとします。利用者は、これを第三者に利用させ、または貸与、譲渡、名義変更、売買などをしてはならないものとします。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>2<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社は、登録情報によって本サービスの利用があった場合、利用登録をおこなった本人が利用したものと扱うことができ、当該利用によって生じた結果ならびにそれに伴う一切の責任については、利用登録を行った本人に帰属するものとします。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>3<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>利用者は、登録情報の不正使用によって当社または第三者に損害が生じた場合、当社および第三者に対して、当該損害を賠償するものとします。 </p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>4<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>登録情報の管理は、利用者が自己の責任の下で行うものとし、登録情報が不正確または虚偽であったために利用者が被った一切の不利益および損害に関して、当社は責任を負わないものとします。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>5<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>登録情報が盗用されまたは第三者に利用されていることが判明した場合、利用者は直ちにその旨を当社に通知するとともに、当社からの指示に従うものとします。</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第６条（個人情報等の取り扱い）</p>

            <p>&nbsp;</p>

            <p style='margin-left:12.0pt'>個人情報及び利用者情報については、当社が別途定める「SEN POINTプロジェクトサービスプライバシーポリシー」に則り、適正に取り扱うこととします。</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第７条（禁止行為）</p>

            <p>&nbsp;</p>

            <p style='margin-left:12.0pt'>本サービスの利用に際し、当社は、利用者に対し、次に掲げる行為を禁止します。当社において、利用者が禁止事項に違反したと認めた場合、利用者用の一時停止、アカウント停止処分その他当社が必要と判断した措置を取ることができます。</p>

            <p style='margin-left:12.0pt'>&nbsp;</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(1)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>本サービスの利用に際し、当社は、利用者に対し、次に掲げる行為を禁止します。当社において、利用者が禁止事項に違反したと認めた場合、利用者用の一時停止、アカウント停止処分その他当社が必要と判断した措置を取ることができます。 </p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(2)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社または第三者の財産を侵害する行為、または侵害する恐れのある行為</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(3)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社または第三者に経済的損害を与える行為</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(4)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社または第三者に対する脅迫的な行為</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(5)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>コンピューターウィルス、有害なプログラムを仕様またはそれを誘発する行為</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(6)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>本サービス用インフラ設備に対して過度な負担となるストレスをかける行為</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(7)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当サイトのサーバーやシステム、セキュリティへの攻撃 p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(8)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社提供のインターフェース以外の方法で当社サービスにアクセスを試みる行為</p>

            <p style='margin-left:30.0pt;text-indent:-18.0pt'>(9)<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>上記の他、当社が不適切と判断する行為</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第８条（免責）</p>

            <p>&nbsp;</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'> 1 <span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社は、本サービスの内容変更、中断、終了によって生じたいかなる損害についても、一切責任を負いません。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'> 2 <span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社は、利用者の本サービスの利用環境について一切関与せず、また一切の責任を負いません。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'> 3 <span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社は、本サービスが利用者の特定の目的に適合すること、期待する機能・商品的価値・正確性・有用性を有すること、利用者による本サービスの利用が利用者に適用のある法令または業界団体の内部規則等に適合すること、および不具合が生じないことについて、何ら保証するものではありません。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'> 4 <span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社は、本サービスが全ての情報端末に対応していることを保証するものではなく、本サービスの利用に供する情報端末のＯＳのバージョンアップ等に伴い、本サービスの動作に不具合が生じる可能性があることにつき、利用者はあらかじめ了承するものとします。当社は、かかる不具合が生じた場合に当社が行うプログラムの修正等により、当該不具合が解消されることを保証するものではありません。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'> 5 <span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>利用者は、AppStore、GooglePlay等のサービスストアの利用規約および運用方針の変更等に伴い、本サービスの一部又は全部の利用が制限される可能性があることをあらかじめ了承するものとします。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'> 6 <span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社は、本サービスを利用したことにより直接的または間接的に利用者に発生した損害について、一切賠償責任を負いません。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'> 7 <span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社は、利用者その他の第三者に発生した機会逸失、業務の中断その他いかなる損害（間接損害や逸失利益を含みます）に対して、当社が係る損害の可能性を事前に通知されていたとしても、一切の責任を負いません。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'> 8 <span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>第１項から前項までの規定は、当社に故意または重過失が存する場合又は契約書が消費者契約法上の消費者に該当する場合には適用しません。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'> 9 <span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>前項が適用される場合であっても、当社は、過失（重過失を除きます。）による行為によって利用者に生じた損害のうち、特別な事情から生じた損害については、一切賠償する責任を負わないものとします。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'>10 <span
              style='font:7.0pt "Times New Roman"'> </span>本サービスの利用に関し当社が損害賠償責任を負う場合、当該損害が発生した月に利用者から受領した利用額を限度として賠償責任を負うものとします。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'>11 <span
              style='font:7.0pt "Times New Roman"'> </span>利用者と他の利用者との間の紛争及びトラブルについて、当社は一切責任を負わないものとします。利用者と他の利用者でトラブルになった場合でも、両者同士の責任で解決するものとし、当社には一切の請求をしないものとします。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'>12 <span
              style='font:7.0pt "Times New Roman"'> </span>利用者は、本サービスの利用に関連し、他の利用者に損害を与えた場合または第三者との間に紛争を生じた場合、自己の費用と責任において、かかる損害を賠償またはかかる紛争を解決するものとし、当社には一切の迷惑や損害を与えないものとします。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'>13 <span
              style='font:7.0pt "Times New Roman"'> </span>利用者の行為により、第三者から当社が損害賠償等の請求をされた場合には、利用者の費用（弁護士費用）と責任で、これを解決するものとします。当社が、当該第三者に対して、損害賠償金を支払った場合には、利用者は、当社に対して当該損害賠償金を含む一切の費用（弁護士費用及び逸失利益を含む）を支払うものとします。</p>

            <p style='margin-left:27.0pt;text-indent:-15.0pt'>14 <span
              style='font:7.0pt "Times New Roman"'> </span>利用者が本サービスの利用に関連して当社に損害を与えた場合、利用者の費用と責任において当社に対して損害を賠償（訴訟費用及び弁護士費用を含む）するものとします。</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第９条（広告の掲載について）</p>

            <p>&nbsp;</p>

            <p style='margin-left:12.0pt;'>利用者は、本サービス上にあらゆる広告が含まれる場合があること、当社またはその提携先があらゆる広告を掲載する場合があることを理解しこれを承諾したものとみなします。本サービス上の広告の形態や範囲は、当社によって随時変更されます。 </p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第１０条（権利譲渡の禁止）</p>

            <p>&nbsp;</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>1<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>利用者は、予め当社の書面による承諾がない限り、本規約上の地位および本規約に基づく権利または義務の全部または一部を第三者に譲渡してはならないものとします。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>2<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社は、本サービスの全部または一部を当社の裁量により第三者に譲渡することができ、その場合、譲渡された権利の範囲内で利用者のアカウントを含む、本サービスに係る利用者の一切の権利が譲渡先に移転するものとします。</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第１１条（分離可能性）</p>

            <p>&nbsp;</p>

            <p style='margin-left:12.0pt;'>本規約のいずれかの条項又はその一部が、消費者契約法その他の法令等により無効又は執行不能と判断された場合であっても、本規約の残りの規定及び一部が無効又は執行不能と判断された規定の残りの部分は、継続して完全に効力を有するものとします。</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第１２条（当社への連絡方法）</p>

            <p>&nbsp;</p>

            <p style='margin-left:12.0pt;'>本サービスに関する利用者の当社へのご連絡・お問い合わせは、本サービスまたは当社が運営するwebサイト内の適宜の場所に設置するお問い合わせフォームからの送信または当社が別途指定する方法により行うものとします。</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>第１３条（準拠法、管轄裁判所）</p>

            <p>&nbsp;</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>1<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>本規約の有効性、解釈及び履行については、日本法に準拠し、日本法に従って解釈されるものとする。</p>

            <p style='margin-left:24.0pt;text-indent:-12.0pt'>2<span
              style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span>当社と利用者等との間での論議・訴訟その他一切の紛争については、訴額に応じて、東京簡易裁判所又は東京地方裁判所を専属的合意管轄裁判所とします｡</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

            <p>２０１８年１月１日　施行</p>

            <p>&nbsp;</p>

            <p>&nbsp;</p>

          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </div>
</template>

<script>
  import router from '@/router'

  export default {
    data () {
      return {
        back () {
          router.go(-1)
        }
      }
    },
    methods: {},
    mounted () {
      this.$store.dispatch('device/init', {
        callback: function (isDeviceReady) {
          if (isDeviceReady) {
            this.$store.dispatch('app/setShowDrawer', true)
            this.$store.dispatch('app/init')
          }
        }
      })
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  .desc-terms-of-service p {
    margin: 0cm;
    margin-bottom: .0001pt;
    line-height: 115%;
    font-size: 11.0pt;
    font-family: "Arial", sans-serif;
    color: black;
  }
</style>
