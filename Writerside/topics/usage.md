# Usage

<note>
BatterySupporterを使用するには、Googleアカウントが必要です。
</note>

[//]: # (Dashboard)
<chapter>
<title>Dashboard</title>
<img src="dashboard.png" alt="dashboard image"/>
<p>監視中のタスクやアカウントなど、基本的な情報を一覧表示しています。</p>

<chapter>
<title>監視中のタスク</title>
<p>サインインしたGoogleアカウントのGoogleTasksに登録されているタスクのうち、バッテリを消費する必要があるものと判断されたタスクを一覧表示します。</p>
<p>ここに表示されるタスクの個数は、充電アラートを表示する際の判断材料となります。</p>
<note>
<p>タスクは、クリックすることでその内容と、設定されている期限を確認できます。</p>
</note>
</chapter>

<chapter>
<title>監視のON/OFF</title>
<p>ONにした場合、タスクの個数とデバイスのバッテリ残量が指定の基準値を超えるもしくは下回った際に、充電アラートを表示されます。</p>
</chapter>

<chapter>
<title>アカウント</title>
<p>サインインボタンをクリックすることで、Googleアカウントでのサインインを行えます。</p>
<p>サインインしたGoogleアカウントの、GoogleTasksに作成したタスクをBatterySupporterで監視することができます。</p>
</chapter>
</chapter>

[//]: # (Task list)
<chapter>
<title>Task list</title>
<img src="task-list.png" alt="task list image"/>
<p>GoogleアカウントのGoogleTasksから取得したタスクを、そのタスクがバッテリを消費するものなのか、消費しないものなのかを分類し、一覧で表示します。</p>

<chapter>
<title>バッテリを消費するタスク</title>
<p>
バッテリを消費すると判断されたタスクが表示されます。<br/>
タスクのタイトルの左側にあるアイコンボタンをクリックすることで、バッテリを消費しないタスクとして変更できます。
</p>
<p>ここに表示されるタスクは、Dashboardで、「監視中のタスク」として一覧表示されます。</p>
<note>
<p>タスクは、クリックすることでその内容と、設定されている期限を確認できます。</p>
</note>
</chapter>

<chapter>
<title>バッテリを消費しないタスク</title>
<p>
バッテリを消費しないと判断されたタスクが表示されます。<br/>
タスクのタイトルの左側にあるアイコンボタンをクリックすることで、バッテリを消費するタスクとして変更できます。
</p>
</chapter>
</chapter>

[//]: # (Settings)
<chapter>
<title>Settings</title>
<img src="settings.png" alt="settings image"/>
<p>アプリケーションの挙動についての設定を行います。</p>

<chapter>
<title>起動設定</title>
<p>「サインイン時に起動」をONにすると、デバイスでサインインした際に、BatterySupporterが自動で起動します。</p>
<p>「システムトレイに最小化」をONにすると、ウィンドウのクローズボタンをクリックした際に、BatterySupporterは終了せず、システムトレイに最小化されます。</p>
<note>
システムトレイに最小化した場合、トレイアイコンをクリックしてウィンドウを表示でき、右クリックして「Quit」をクリックすることで、BatterySupporterを終了できます。
</note>
</chapter>

<chapter>
<title>通知設定</title>
<p>「バッテリの残量不足を通知」をONにすると、バッテリの残量がタスクの量に対して不足していると判断された場合にプッシュ通知を受け取られます。</p>
</chapter>

<chapter>
<title>バッテリ残量不足の判断基準</title>
<p>「タスクの個数」に、判断基準とするタスクの個数を入力します。</p>
<p>「バッテリの残量」に、判断基準とするバッテリの残量を入力します。</p>
<note>
「バッテリが残量不足である」ことの判定は、バッテリを消費するモノであると分類されたタスクの個数が「タスクの個数」以上であり、デバイスの現在のバッテリ残量が「バッテリの残量」以下であることを基準にしています。
<br/>
</note>
<p>以下は、バッテリの残量が不足していると判断する際の式です。</p>
<code-block>
a = 「バッテリの残量不足の判定基準」に設定した、「タスクの個数」
b = 「バッテリの残量不足の判定基準」に設定した、「バッテリの残量」
A = Dashboardで「監視中のタスク」に一覧表示されているタスクの個数（バッテリを消費するモノであると分類されたタスクの個数）
B = デバイスの現在のバッテリ残量
|
a ≦ A かつ b ≧ B の時、「バッテリの残量が不足している」と判断します。
</code-block>
</chapter>
</chapter>

[//]: # (Help)
<chapter>
<title>Help</title>
<img src="help.png" alt="help image"/>
<p>BatterySupporterの使用方法を記載したドキュメントへのリンクや、フェードバックレポートを送信するためのフォームを設けています。</p>

<chapter>
<title>フェードバックレポートの提出</title>
<p>BatterySupporterを使用するうえで見つけられた問題や、改善すべき点などについてのレポートを提出していただくことが可能です。</p>
<note>
<p>メールアドレスの入力は必須項目ではありません。タイトルと内容を入力していただければ、「SEND」ボタンをクリックしていただくことで送信が可能です。</p>
<p>返信を希望される場合は、メールアドレスの入力をお願いします。</p>
</note>
</chapter>

<chapter>
<title>Links</title>
<p>BatterySupporterのウェブサイト及び、ドキュメンテーションへのリンクを記載しています。</p>
</chapter>
</chapter>

[//]: # (About)
<chapter>
<title>About</title>
<img src="about.png" alt="about image"/>
<p>BatterySupporterについての全般的な情報を記載しています。</p>

<chapter>
<title>Information</title>
<p>BatterySupporterの情報が記載されています。</p>
<p>「Current version」には、現在使用されているBatterySupporterのバージョンが、「Release date」には、そのバージョンのBatterySupporterがリリースされた日付が記載されています。</p>
</chapter>

<chapter>
<title>Links</title>
<p>BatterySupporterのウェブサイト及び、ドキュメンテーションへのリンクを記載しています。</p>
</chapter>

<chapter>
<title>Release note</title>
<p>リリースされたBatterySupporterの、それぞれのバージョンでの変更内容について記載しています。</p>
<note title="バージョンの表現について">
1.x.x の 1

- メジャーバージョン：アプリケーションに大幅な変更が加わった際に増加します。

x.0.x の 0

- マイナーバージョン：既存のコードなどに影響を与えず、アプリケーションに新機能を追加した際に増加します。

x.x.0 の 0

- パッチバージョン：バグ修正やセキュリティ更新など、機能には影響しない小さな修正をした際に増加します。
</note>
</chapter>
</chapter>

