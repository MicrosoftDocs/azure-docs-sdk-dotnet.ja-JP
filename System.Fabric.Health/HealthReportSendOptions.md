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
      <para>送信するときに適用される送信オプションを表す、<see cref="T:System.Fabric.Health.HealthReport" />です。</para>
    </summary>
    <remarks>
      <para>レポートは、正常性を使用してストアに送信できます<see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />です。</para>
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
          <para><see cref="T:System.Fabric.Health.HealthReportSendOptions" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>既定では、送信のオプション セットはありません。 Fabric クライアント設定を使用してレポートを送信するタイミングと再試行するときに決定は、エラー発生時に送信します。</remarks>
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
            取得または設定をレポートをすぐに送信するかどうかを示すフラグ。
            既定値は false、その場合、レポートが送信される、ファブリック クライアントの正常性ごとでは、関連する設定を報告します。
            </summary>
        <value>レポートをすぐに送信するかどうかを示すフラグ。</value>
        <remarks>
          <para>
            場合<languageKeyword>true</languageKeyword>、レポートに関係なく、すぐに送信されるが、<see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" />構成正常性のクライアントのセットします。
            これは、重要なレポートをできるだけ早く送信するのに便利です。
            ここで便利ですが、もう 1 つのシナリオは、かどうか、クライアント閉じる必要があります、たとえば、ホスト プロセスが下がり、送信されるレポートの確率を高めることが必要です。
            タイミングとその他の条件では、によって、レポートを送信する可能性があります依然として失敗、クライアントは、シャット ダウンする前に送信にかかる時間があるないため、またはメッセージが失われ、それを再試行できる前に、正常性のクライアントが停止したためです。
            </para>
          <para>
            場合<languageKeyword>false</languageKeyword>、正常性のクライアント設定に基づいて、レポートを送信、特に<see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" />構成します。
            </para>
          <para>
            既定では、レポートはすぐに送信されません。
            これは、正常性のクライアントの正常性レポートの正常性レポート処理と同様に正常性ストアへのメッセージを最適化するためにできるので、推奨される設定です。 
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>