<Type Name="DeployedServicePackageHealthReport" FullName="System.Fabric.Health.DeployedServicePackageHealthReport">
  <TypeSignature Language="C#" Value="public class DeployedServicePackageHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeployedServicePackageHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class DeployedServicePackageHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthReport = class&#xA;    inherit HealthReport" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthReport</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>展開済みサービス パッケージの正常性エンティティに適用される正常性レポートを表します。 </para>
    </summary>
    <remarks>レポートは、正常性を使用してストアに送信できます<see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />です。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthReport (Uri applicationName, string serviceManifestName, string nodeName, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string serviceManifestName, string nodeName, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthReport.#ctor(System.Uri,System.String,System.String,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.DeployedServicePackageHealthReport : Uri * string * string * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.DeployedServicePackageHealthReport" Usage="new System.Fabric.Health.DeployedServicePackageHealthReport (applicationName, serviceManifestName, nodeName, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション名。 null または空にすることはできません。</para>
        </param>
        <param name="serviceManifestName">
          <para>サービス マニフェスト名です。 null または空にすることはできません。</para>
        </param>
        <param name="nodeName">
          <para>ノード名。 null または空にすることはできません。</para>
        </param>
        <param name="healthInformation">
          <para><see cref="T:System.Fabric.Health.HealthInformation" /> SourceId、プロパティ、ヘルス状態と同様に、レポート フィールドを記述します。 必須。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Health.DeployedServicePackageHealthReport" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>サービス マニフェスト名を null にすることはできません。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>サービス マニフェスト名が正しくありません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthReport (Uri applicationName, string serviceManifestName, string servicePackageActivationId, string nodeName, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string nodeName, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthReport.#ctor(System.Uri,System.String,System.String,System.String,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.DeployedServicePackageHealthReport : Uri * string * string * string * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.DeployedServicePackageHealthReport" Usage="new System.Fabric.Health.DeployedServicePackageHealthReport (applicationName, serviceManifestName, servicePackageActivationId, nodeName, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション名。 null または空にすることはできません。</para>
        </param>
        <param name="serviceManifestName">
          <para>サービス マニフェスト名です。 null または空にすることはできません。</para>
        </param>
        <param name="servicePackageActivationId">
          <para>
            <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービス パッケージのです。 これを使用して取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。 
            </para>
          <para>
            場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
        </param>
        <param name="nodeName">
          <para>ノード名。 null または空にすることはできません。</para>
        </param>
        <param name="healthInformation">
          <para><see cref="T:System.Fabric.Health.HealthInformation" /> SourceId、プロパティ、ヘルス状態と同様に、レポート フィールドを記述します。 必須。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Health.DeployedServicePackageHealthReport" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>サービス マニフェスト名を null にすることはできません。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>サービス マニフェスト名が正しくありません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthReport.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedServicePackageHealthReport.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アプリケーションの名前を取得します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Uri" />アプリケーション名を表すです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthReport.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedServicePackageHealthReport.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>展開済みサービス パッケージが実行されているノードの名前を取得します。</para>
        </summary>
        <value>
          <para>A<see cref="T:System.String" />ノード名を表すです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthReport.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Health.DeployedServicePackageHealthReport.ServiceManifestName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス マニフェスト名を取得します。</para>
        </summary>
        <value>
          <para>A<see cref="T:System.String" />サービス マニフェスト名を表すです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthReport.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Health.DeployedServicePackageHealthReport.ServicePackageActivationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス パッケージの ActivationId を取得します。
            </summary>
        <value>
          <para>
            <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービス パッケージのです。 これを使用して取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。 
            </para>
          <para>
            場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>