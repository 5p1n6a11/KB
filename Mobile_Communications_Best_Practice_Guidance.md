# Mobile Communications Best Practice Guidance

モバイル通信のベストプラクティスガイダンス

## References

https://www.cisa.gov/sites/default/files/2024-12/guidance-mobile-communications-best-practices.pdf

## Introduction

はじめに

The Cybersecurity and Infrastructure Security Agency (CISA) has identified cyber espionage activity by People’s Republic of China (PRC) government-affiliated threat actors targeting commercial telecommunications infrastructure. This activity enabled the theft of customer call records and the compromise of private communications for a limited number of highly targeted individuals. While applicable to all audiences, this guidance specifically addresses “highly targeted” individuals who are in senior government or senior political positions and likely to possess information of interest to these threat actors. CISA is releasing this best practice guidance to promote protections for mobile communications from exploitation by PRC-affiliated and other malicious cyber threat actors.

サイバーセキュリティ・インフラストラクチャセキュリティ機関（CISA）は、中華人民共和国（PRC）政府と関連のある脅威行為者による商業用通信インフラストラクチャを標的としたサイバースパイ行為を確認しました。この活動により、限られた数の標的を絞った個人を対象に、顧客の通話記録の盗難や、プライベートな通信の侵害が可能になりました。このガイダンスは、あらゆる対象に適用されますが、特に政府高官や政治家の地位にあり、これらの脅威行為者に興味を持たれる情報を保有している可能性が高い「標的を絞った」個人を対象としています。CISAは、中国共産党関連およびその他の悪意あるサイバー脅威行為者による悪用からモバイル通信を保護することを目的として、このベストプラクティス・ガイダンスを公表しています。

## Best Practices

ベストプラクティス

CISA strongly urges highly targeted individuals to immediately review and apply the best practices below to protect mobile communications. Highly targeted individuals should assume that all communications between mobile devices—including government and personal devices—and internet services are at risk of interception or manipulation. While no single solution eliminates all risks, implementing these best practices significantly enhances protection of sensitive communications against government-affiliated and other malicious cyber actors. Organizations may already have these best practices in place, such as secure communication platforms[^1] and multifactor authentication (MFA) policies. In cases where organizations do not, apply the following best practices to your mobile devices.

CISAは、標的とされる可能性の高い個人に対して、モバイル通信を保護するために、以下のベストプラクティスを直ちに確認し、適用するよう強く推奨します。標的とされる可能性の高い個人においては、政府および個人所有のデバイスを含むモバイルデバイスとインターネットサービス間のすべての通信が傍受または操作されるリスクがあることを想定すべきです。単一のソリューションですべてのリスクを排除することはできませんが、これらのベストプラクティスを導入することで、政府関係者やその他の悪意のあるサイバー犯罪者による機密通信の保護が大幅に強化されます。企業はすでに、セキュアな通信プラットフォーム[^2]や多要素認証（MFA）ポリシーなどのベストプラクティスを導入しているかもしれません。そうでない場合は、以下のベストプラクティスをモバイルデバイスに適用してください。

[^1]: Some examples include, but are not limited to, Microsoft Teams, Google Workspace, Slack, and WebEx.

[^2]: 例としては、Microsoft Teams、Google Workspace、Slack、WebExなどが含まれますが、これらに限定されません。

### General Recommendations

一般的な推奨事項

Apply these best practices to your devices and online accounts.

これらのベストプラクティスを、あなたのデバイスやオンラインアカウントに適用してください。

(1) Use only end-to-end encrypted communications.

(1) エンドツーエンドで暗号化された通信のみを使用してください。

Adopt a free messaging application for secure communications that guarantees end-to-end encryption, such as Signal or similar apps. CISA recommends an end-to-end encrypted messaging app that is compatible with both iPhone and Android operating systems, allowing for text message interoperability across platforms. Such apps may also offer clients for MacOS, Windows, and Linux, and sometimes the web. These apps typically support one-on-one text chats, group chats with up to 1,000 participants, and encrypted voice and video calls. Additionally, they may include features like disappearing messages and images, which can enhance privacy. When selecting an end-to-end encrypted messaging app, evaluate the extent to which the app and associated services collect and store metadata.

エンドツーエンドの暗号化を保証する、安全な通信のための無料メッセージングアプリケーションを採用する。CISAは、iPhoneとAndroidの両方のオペレーティングシステムと互換性があり、プラットフォーム間のテキストメッセージの相互運用を可能にする、エンドツーエンドの暗号化メッセージングアプリケーションを推奨しています。このようなアプリケーションは、MacOS、Windows、Linux用のクライアントを提供している場合もあり、ウェブ版の場合もあります。これらのアプリは通常、1対1のテキストチャット、最大1,000人の参加者が可能なグループチャット、暗号化された音声およびビデオ通話をサポートしています。さらに、メッセージや画像が自動的に消える機能など、プライバシーを強化する機能が含まれている場合もあります。エンドツーエンド暗号化メッセージングアプリを選択する際には、アプリおよび関連サービスがメタデータを収集および保存する範囲を評価してください。

(2) Enable Fast Identity Online (FIDO) phishing-resistant authentication. FIDO authentication uses the strongest form of MFA and is effective against MFA bypass techniques. Where feasible, hardwarebased FIDO security keys, such as Yubico or Google Titan, are the most effective; however, FIDO passkeys are an acceptable alternative.

(2) フィッシング対策認証であるFast Identity Online（FIDO）を有効にする。FIDO認証は、MFAの最も強力な形態であり、MFAのバイパス技術に対しても有効です。可能な場合は、YubicoやGoogle TitanなどのハードウェアベースのFIDOセキュリティキーが最も効果的ですが、FIDOパスキーも代替手段として有効です。

Take inventory of valuable accounts, including email and social media. Review any accounts where information leakage would benefit threat actors.

電子メールやソーシャルメディアを含む、重要なアカウントの棚卸しを行う。情報漏洩が脅威をもたらすアクターに利益をもたらす可能性があるアカウントをすべて確認する。

Enroll each account in FIDO-based authentication, especially Microsoft, Apple, and Google accounts. Once enrolled in FIDO-based authentication, disable other, less secure forms of MFA.

特にMicrosoft、Apple、GoogleのアカウントをFIDOベースの認証に登録する。FIDOベースの認証に登録したら、より安全性の低い他のMFAを無効にする。

For Gmail users, enroll in Google’s Advanced Protection (APP) program, as it strengthens your defenses against phishing and account hijacking.

Gmailユーザーは、Googleの高度な保護（APP）プログラムに登録すると、フィッシングやアカウント乗っ取りに対する防御が強化されます。

(3) Migrate away from Short Message Service (SMS)-based MFA. Do not use SMS as a second factor for authentication. SMS messages are not encrypted—a threat actor with access to a telecommunication provider’s network who intercepts these messages can read them. SMS MFA is not phishing-resistant and is therefore not strong authentication for accounts of highly targeted individuals.

(3) ショートメッセージサービス（SMS）ベースの多要素認証から移行する。SMSを認証の第2要素として使用しない。SMSメッセージは暗号化されていないため、通信プロバイダーのネットワークにアクセスし、メッセージを傍受する脅威行為者は、メッセージを読み取ることができる。SMS多要素認証はフィッシングに強くなく、したがって、標的が絞られた個人のアカウントに対する強力な認証とは言えない。

Note: Some online services may default to SMS during account recovery flows; it may not be feasible for you to completely eliminate SMS messages from the service.

注：一部のオンラインサービスでは、アカウント復旧フロー中にSMSがデフォルトで使用される場合があります。サービスからSMSメッセージを完全に排除することはできない場合があります。

For less valuable accounts, use other forms of MFA such as authenticator codes. Set up these accounts with a free authenticator application for MFA, such as Google Authenticator, Microsoft Authenticator, or Authy.

価値の低いアカウントには、認証コードなどの他の多要素認証方式を使用します。Google Authenticator、Microsoft Authenticator、Authyなどの多要素認証用の無料認証アプリケーションでこれらのアカウントを設定します。

Note: While authenticator codes are better than SMS, they are still vulnerable to phishing. Only FIDO authentication is phishing-resistant.

注：認証コードはSMSよりも優れていますが、フィッシングには依然として脆弱です。フィッシングに耐性があるのはFIDO認証のみです。

Once enrolled, disable SMS for each account. Enrollment in authenticator-based MFA does not automatically unenroll the account’s SMS. This can create a weak, exploitable fallback mechanism that can be exploited by threat actors.

登録後、各アカウントのSMSを無効にします。認証機能ベースのMFAに登録しても、アカウントのSMSが自動的に登録解除されるわけではありません。これにより、脅威の主体に悪用される脆弱な代替手段が生まれる可能性があります。

(4) Use a password manager to store all passwords. Some password managers, such as the Apple Passwords app, LastPass, 1Password, Google Password Manager, Dashlane, Keeper, and Proton Pass, automatically alert on weak, reused, or leaked passwords. Additionally, some of these password managers generate authenticator codes.

(4) すべてのパスワードを保存するには、パスワードマネージャーを使用します。Apple Passwords アプリ、LastPass、1Password、Google Password Manager、Dashlane、Keeper、Proton Pass などの一部のパスワードマネージャーは、脆弱なパスワード、使い回しパスワード、流出したパスワードを自動的に警告します。さらに、これらのパスワードマネージャーの一部は認証コードを生成します。

Protect the vault (primary) password with a strong passphrase (i.e., long, unique, and random).

金庫室の（プライマリ）パスワードを強力なパスフレーズ（すなわち、長く、独自で、ランダムな）で保護する。

Review existing passwords to ensure they are long, unique, and random. If they are not, change to passwords generated by the password manager. See CISA’s Use Strong Passwords guidance for more information.

既存のパスワードを再確認し、長さ、一意性、ランダム性が確保されていることを確認してください。そうでない場合は、パスワード管理ツールで生成されたパスワードに変更してください。詳細は、CISAの「Use Strong Passwords（強力なパスワードを使用する）」を参照してください。

(5) Set a Telco PIN. Most telecommunications providers offer the ability to set an additional PIN or passcode for your mobile phone account. This PIN is required for logging into your account or completing sensitive operations, such as porting your phone number—a critical step in countering subscriber identity module (SIM)-swapping techniques.

(5) 電話会社のPINを設定する。ほとんどの通信事業者は、携帯電話のアカウントに追加のPINまたはパスコードを設定する機能を提供しています。このPINは、アカウントへのログインや、SIMスワップ技術に対抗するための重要なステップである電話番号の移行など、機密性の高い操作を実行する際に必要となります。

Add a PIN and MFA to your mobile carrier account to reduce the risk of SIM-swapping techniques. Then, use your password manager to change your mobile account password.

SIMスワップ技術のリスクを軽減するために、モバイルキャリアのアカウントにPINとMFAを追加します。次に、パスワードマネージャーを使用してモバイルアカウントのパスワードを変更します。

(6) Regularly update software.

(6) ソフトウェアを定期的に更新する。

Regularly update operating systems and applications on mobile devices. Check weekly to ensure devices are up to date.

モバイルデバイスのオペレーティングシステムとアプリケーションを定期的に更新する。デバイスが最新の状態であることを確認するために、毎週チェックする。

Enable auto-update on mobile devices to ensure timely patching of the operating system and applications.

モバイルデバイスで自動更新を有効にすると、オペレーティングシステムやアプリケーションのパッチをタイムリーに適用できます。

(7) Opt for the latest hardware version from your cell phone manufacturer. Newer hardware often incorporates critical security features that older hardware cannot support. Without the most recent version of the hardware, software updates alone will not provide the maximum available security benefits.

(7) 携帯電話メーカーから提供されている最新のハードウェアバージョンを選択してください。新しいハードウェアには、古いハードウェアではサポートできない重要なセキュリティ機能が組み込まれていることがよくあります。最新のハードウェアを使用しない場合、ソフトウェアのアップデートだけでは最大限のセキュリティ上のメリットを得ることはできません。

(8) Do not use a personal virtual private network (VPN). Personal VPNs simply shift residual risks from your internet service provider (ISP) to the VPN provider, often increasing the attack surface. Many free and commercial VPN providers have questionable security and privacy policies. However, if your organization requires a VPN client to access its data, that is a different use case.

(8) 個人用 VPN（仮想プライベートネットワーク）は使用しないでください。個人用 VPN は、インターネットサービスプロバイダ（ISP）から VPN プロバイダに残留リスクを移行するだけであり、多くの場合、攻撃対象領域を拡大することになります。多くの無料および商用の VPN プロバイダは、セキュリティおよびプライバシーポリシーに疑問が残ります。ただし、組織が VPN クライアントを使用してデータにアクセスする必要がある場合は、これは異なる使用事例となります。

### iPhone-Specific Recommendations

iPhone 固有の推奨事項

The below recommendations are specific to iPhone users to enhance protections of mobile communications.

以下は、モバイル通信の保護を強化するためのiPhoneユーザー向けの具体的な推奨事項です。

(1) Enable Lockdown Mode. Lockdown mode strictly limits certain apps, websites, and features, or makes some features unavailable, to reduce the attack surface that could potentially be exploited by threat actors.

(1) ロックダウンモードを有効にします。ロックダウンモードは、特定のアプリ、ウェブサイト、および機能を厳しく制限したり、一部の機能を無効にしたりすることで、脅威の主体によって悪用される可能性のある攻撃対象領域を縮小します。

(2) Disable the following setting to ensure messages do not send as SMS if iMessage is unavailable. iMessage offers end-to-end encryption between Apple users.

(2) iMessageが利用できない場合でもメッセージがSMSとして送信されないようにするには、以下の設定を無効にします。iMessageは、Appleユーザー間のエンドツーエンドの暗号化を提供します。

Disable: Settings -> Apps -> Messages -> “Send as Text Message”

無効にする：設定 -> アプリ -> メッセージ -> 「テキストメッセージとして送信」

(3) Protect your Domain Name System (DNS) queries. Apple iCloud Private Relay provides enhanced privacy and security; as a partial free alternative, use encrypted DNS services for iOS from providers such as Cloudflare’s 1.1.1.1 Resolver, Google’s 8.8.8.8 Resolver, and Quad9’s 9.9.9.9 Resolver. These services support encrypted DNS to prevent interception and manipulation by threat actors.

(3) お客様の DNS（ドメインネームシステム）クエリを保護します。Apple iCloud Private Relay は、プライバシーとセキュリティを強化します。一部無料の代替策として、Cloudflare の 1.1.1.1 リゾルバ、Google の 8.8.8.8 リゾルバ、Quad9 の 9.9.9.9 リゾルバなどのプロバイダーが提供する iOS 用の暗号化 DNS サービスをご利用ください。これらのサービスは、脅威をもたらす行為者による傍受や操作を防止するために暗号化 DNS をサポートしています。

(4) Enroll in Apple iCloud Private Relay. For additional protections, enroll in Apple iCloud Private Relay (see the iCloud User Guide for configuration instructions). Private Relay ensures iCloud devices use secure DNS, masks IP addresses, and splits traffic between servers controlled by Apple and a third party to reduce the chances that a single entity can link browser behavior to the user’s identity.

(4) Apple iCloud Private Relay に登録します。 さらに保護を強化するには、Apple iCloud Private Relay に登録します（設定方法については、iCloud ユーザガイドを参照してください）。 Private Relay は、iCloud デバイスが安全な DNS を使用し、IP アドレスをマスクし、Apple とサードパーティが管理するサーバー間のトラフィックを分割することで、単一のエンティティがブラウザの動作をユーザの ID に結びつける可能性を低減します。

Note: These benefits are limited to the Safari browser.

注：これらの特典はSafariブラウザに限定されます。

(5) Review and restrict app permissions through Settings -> Privacy & Security. Review which apps access sensitive data, such as location, camera, and microphone. Revoke and avoid granting permissions that are unnecessary or excessive for functionality of the app.

(5) [設定] -> [プライバシーとセキュリティ] からアプリの権限を再確認し、制限します。位置情報、カメラ、マイクなど、機密データにアクセスするアプリを確認します。アプリの機能にとって不必要または過剰な権限は取り消し、付与しないようにします。

### Android-Specific Recommendations

Android 固有の推奨事項

The below recommendations are specific to Android users to enhance protections of mobile communications.

以下は、モバイル通信の保護を強化するためのAndroidユーザー向けの具体的な推奨事項です。

(1) Prioritize models from manufacturers with strong security track records and long-term security update commitments. For example, review Android’s Enterprise Recommended knowledge worker and dedicated devices to ensure models meet security and update standards. By combining up-to-date hardware with regular software updates, Android users can take full advantage of the platform’s evolving security enhancements. Prioritize models that:

(1) セキュリティ対策に実績があり、長期的なセキュリティアップデートの提供を約束しているメーカーの機種を優先する。例えば、Androidのエンタープライズ推奨の知識労働者向けおよび専用端末を検討し、機種がセキュリティおよびアップデートの基準を満たしていることを確認する。最新のハードウェアと定期的なソフトウェアアップデートを組み合わせることで、Androidユーザーは、進化するプラットフォームのセキュリティ強化を最大限に活用することができます。優先すべき機種は以下の通りです。

Support hardware-level security features-often referred to as secure enclave or hardware security module (HSM)-to enable secure storage of cryptographic keys.

暗号鍵の安全な保存を可能にするため、セキュアエンクレーブまたはハードウェアセキュリティモジュール（HSM）と呼ばれることが多いハードウェアレベルのセキュリティ機能に対応しています。

Offer security updates at least monthly.

少なくとも毎月、セキュリティアップデートを提供すること。

Commit to security updates for at least the next five years.

少なくとも今後5年間はセキュリティアップデートを継続する。

(2) Only use Rich Communication Services (RCS) if end-to-end encryption is enabled. If all participants are using Google Messages, your conversation will use end-to-end encryption. Review Google’s Turn on RCS chats in Google Messages and Use end-to-end encryption in Google Messages for additional guidance.

(2) エンドツーエンド暗号化が有効になっている場合のみ、リッチコミュニケーションサービス（RCS）を使用してください。すべての参加者がGoogleメッセージを使用している場合、会話にはエンドツーエンド暗号化が使用されます。Googleの「GoogleメッセージでRCSチャットを有効にする」および「Googleメッセージでエンドツーエンド暗号化を使用する」を参照してください。

(3) Configure Android Private DNS to use a trusted, high-privacy resolver, such as Cloudflare’s 1.1.1.1 Resolver, Google’s 8.8.8.8 Resolver, and Quad9’s 9.9.9.9 Resolver.

(3) 信頼できる、プライバシー保護の高いリゾルバ、例えばCloudflareの1.1.1.1リゾルバ、Googleの8.8.8.8リゾルバ、Quad9の9.9.9.9リゾルバを使用するようにAndroid Private DNSを設定します。

(4) Confirm Always Use Secure Connections is enabled in the Chrome browser on your Android device to enhance mobile browsing security. This feature should be turned on by default and ensures all website connections default to HTTPS whenever possible, protecting against threat actor interception and manipulation. See Google’s Manage Chrome safety and security guidance.

(4) モバイルブラウジングのセキュリティを強化するため、Android 端末の Chrome ブラウザで「常に安全な接続を使用する」が有効になっていることを確認してください。この機能はデフォルトでオンになっており、脅威をもたらす行為者の傍受や操作から保護するために、可能な場合は常にすべてのウェブサイト接続が HTTPS にデフォルト設定されます。Google の Chrome の安全性とセキュリティに関するガイダンスを参照してください。

(5) Confirm Enhanced Protection for Safe Browsing is enabled in the Chrome browser on your Android device to provide an additional layer of protection against malicious websites, phishing attempts, and harmful downloads. The Safe Browsing feature should be turned on by default and alerts you if you attempt to navigate to potentially dangerous sites or download suspicious files. To enable and optimize this feature, see Google’s Choose your Safe Browsing protection level in Chrome guidance.

(5) 悪意のあるウェブサイト、フィッシング詐欺、有害なダウンロードに対する追加の保護レイヤーを提供するため、Android デバイスの Chrome ブラウザで「セーフブラウジングの拡張保護」が有効になっていることを確認してください。 セーフブラウジング機能はデフォルトでオンになっており、危険な可能性のあるサイトに移動しようとしたり、疑わしいファイルをダウンロードしようとした場合に警告が表示されます。 この機能を有効にして最適化するには、Google の Chrome ガイダンス「セーフブラウジングの保護レベルを選択」を参照してください。

(6) Confirm Google Play Protect is enabled to detect and prevent malicious apps. Regularly review the app scans to identify potential threats. Exercise caution if using third-party app stores or "sideloading" apps from other sources.

(6) Google Play Protectが有効になっており、悪意のあるアプリを検出および防止していることを確認してください。定期的にアプリのスキャンを確認し、潜在的な脅威を特定してください。サードパーティのアプリストアを使用したり、他のソースからアプリを「サイドロード」したりする場合は、注意してください。

(7) Review and restrict app permissions through Settings -> Apps -> Permissions Manager. Revoke permissions that are unnecessary or excessive for the app’s functionality. Unless absolutely required, avoid granting apps access to sensitive permissions such as location, camera, or microphone.

(7) 設定] -> [アプリ] -> [権限マネージャー] からアプリの権限を確認し、制限します。アプリの機能にとって不必要または過剰な権限は取り消します。 絶対に必要でない限り、位置情報、カメラ、マイクなどの機密性の高い権限へのアクセスをアプリに許可することは避けてください。

## Incident Reporting Information

インシデント報告情報

Cyber incidents can be reported to CISA by calling 1-844-Say-CISA (1-844-729-2472), emailing report@cisa.dhs.gov, or reporting online at CISA Services. When available, please include the following information regarding the incident: date, time, and location of the incident; type of activity; number of people affected; type of equipment used for the activity; the name of the submitting company or organization; and a designated point of contact.

サイバーインシデントは、1-844-Say-CISA（1-844-729-2472）に電話するか、report@cisa.dhs.gov にメールするか、CISA Services からオンラインで報告することで CISA に報告することができます。利用可能な場合は、インシデントに関する以下の情報を記載してください：インシデントの日付、時刻、場所；活動の種類；影響を受けた人数；活動に使用された機器の種類；提出元の企業または組織の名称；指定の連絡先。

## Disclaimer

免責事項

CISA does not endorse any commercial entity, product, company, or service, including any entities, products, or services linked within this document. Any reference to specific commercial entities, products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply endorsement, recommendation, or favoring by CISA.

CISAは、本書で言及されているいかなる事業体、製品、会社、サービス（本書で言及されている事業体、製品、サービスを含む）を推奨するものではありません。 サービスマーク、商標、メーカーなどによる特定の事業体、製品、プロセス、サービスへの言及は、CISAによる推奨、推奨、または支持を意味するものではありません。
