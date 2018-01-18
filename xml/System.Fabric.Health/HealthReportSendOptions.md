<Type Name="HealthReportSendOptions" FullName="System.Fabric.Health.HealthReportSendOptions">
  <TypeSignature Language="C#" Value="public sealed class HealthReportSendOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthReportSendOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthReportSendOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthReportSendOptions" />
  <TypeSignature Language="F#" Value="type HealthReportSendOptions = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="be45e-101">送信するときに適用される送信オプションを表す、<see cref="T:System.Fabric.Health.HealthReport" />です。</span><span class="sxs-lookup"><span data-stu-id="be45e-101">Represents the send options that are applied when sending a <see cref="T:System.Fabric.Health.HealthReport" />.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="be45e-102">レポートは、正常性を使用してストアに送信できます<see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />です。</span><span class="sxs-lookup"><span data-stu-id="be45e-102">The report can be sent to the health store using <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HealthReportSendOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthReportSendOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="be45e-103"><see cref="T:System.Fabric.Health.HealthReportSendOptions" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="be45e-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> class.</span></span></para>
        </summary>
        <remarks><span data-ttu-id="be45e-104">既定では、送信のオプション セットはありません。</span><span class="sxs-lookup"><span data-stu-id="be45e-104">By default, there are no send options set.</span></span> <span data-ttu-id="be45e-105">Fabric クライアント設定を使用してレポートを送信するタイミングと再試行するときに決定は、エラー発生時に送信します。</span><span class="sxs-lookup"><span data-stu-id="be45e-105">The fabric client settings are used to determine when to send the report and when to retry send on failure.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Immediate">
      <MemberSignature Language="C#" Value="public bool Immediate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Immediate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthReportSendOptions.Immediate" />
      <MemberSignature Language="VB.NET" Value="Public Property Immediate As Boolean" />
      <MemberSignature Language="F#" Value="member this.Immediate : bool with get, set" Usage="System.Fabric.Health.HealthReportSendOptions.Immediate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be45e-106">取得または設定をレポートをすぐに送信するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="be45e-106">Gets or sets the flag which indicates whether the report should be sent immediately.</span></span>
            <span data-ttu-id="be45e-107">既定値は false、その場合、レポートが送信される、ファブリック クライアントの正常性ごとでは、関連する設定を報告します。</span><span class="sxs-lookup"><span data-stu-id="be45e-107">Defaults to false, in which case the report is sent per the fabric client health report related settings.</span></span>
            </summary>
        <value><span data-ttu-id="be45e-108">レポートをすぐに送信するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="be45e-108">A flag which indicates whether the report should be sent immediately.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="be45e-109">場合<languageKeyword>true</languageKeyword>、レポートに関係なく、すぐに送信されるが、<see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" />構成正常性のクライアントのセットします。</span><span class="sxs-lookup"><span data-stu-id="be45e-109">If <languageKeyword>true</languageKeyword>, the report is sent immediately, regardless of the <see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" /> configuration set on the health client.</span></span>
            <span data-ttu-id="be45e-110">これは、重要なレポートをできるだけ早く送信するのに便利です。</span><span class="sxs-lookup"><span data-stu-id="be45e-110">This is useful for critical reports that should be sent as soon as possible.</span></span>
            <span data-ttu-id="be45e-111">ここで便利ですが、もう 1 つのシナリオは、かどうか、クライアント閉じる必要があります、たとえば、ホスト プロセスが下がり、送信されるレポートの確率を高めることが必要です。</span><span class="sxs-lookup"><span data-stu-id="be45e-111">Another scenario where this may be useful is if the client needs to be closed, for example because the host process is going down, and you need to increase the chances of the report being sent.</span></span>
            <span data-ttu-id="be45e-112">タイミングとその他の条件では、によって、レポートを送信する可能性があります依然として失敗、クライアントは、シャット ダウンする前に送信にかかる時間があるないため、またはメッセージが失われ、それを再試行できる前に、正常性のクライアントが停止したためです。</span><span class="sxs-lookup"><span data-stu-id="be45e-112">Depending on timing and other conditions, sending the report may still fail, either because the client doesn't have time to send it before shutdown, or because the message is lost and the health client went down before it can retry.</span></span>
            </para>
          <para>
            <span data-ttu-id="be45e-113">場合<languageKeyword>false</languageKeyword>、正常性のクライアント設定に基づいて、レポートを送信、特に<see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" />構成します。</span><span class="sxs-lookup"><span data-stu-id="be45e-113">If <languageKeyword>false</languageKeyword>, the report is sent based on the health client settings, especially the <see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" /> configuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="be45e-114">既定では、レポートはすぐに送信されません。</span><span class="sxs-lookup"><span data-stu-id="be45e-114">By default, reports are not sent immediately.</span></span>
            <span data-ttu-id="be45e-115">これは、正常性のクライアントの正常性レポートの正常性レポート処理と同様に正常性ストアへのメッセージを最適化するためにできるので、推奨される設定です。</span><span class="sxs-lookup"><span data-stu-id="be45e-115">This is the recommended setting because it allows the health client to optimize health reporting messages to health store as well as health report processing.</span></span> 
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>