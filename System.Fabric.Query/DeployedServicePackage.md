<Type Name="DeployedServicePackage" FullName="System.Fabric.Query.DeployedServicePackage">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServicePackage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackage" />
  <TypeSignature Language="F#" Value="type DeployedServicePackage = class" />
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
      <para>
            展開済みサービス パッケージをについて説明します。 これは、クエリを使用して取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />の一覧を返す<see cref="T:System.Fabric.Query.DeployedServicePackage" />特定のノードでします。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeployedServicePackageStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.DeploymentStatus DeployedServicePackageStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.DeploymentStatus DeployedServicePackageStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackage.DeployedServicePackageStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServicePackageStatus As DeploymentStatus" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackageStatus : System.Fabric.DeploymentStatus" Usage="System.Fabric.Query.DeployedServicePackage.DeployedServicePackageStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DeploymentStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>展開済みサービス パッケージの状態を取得します。</para>
        </summary>
        <value>
          <para>展開済みサービス パッケージのステータス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackage.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Query.DeployedServicePackage.ServiceManifestName" />
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
          <para>サービス マニフェスト名です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestVersion">
      <MemberSignature Language="C#" Value="public string ServiceManifestVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackage.ServiceManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestVersion As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestVersion : string" Usage="System.Fabric.Query.DeployedServicePackage.ServiceManifestVersion" />
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
          <para>サービス マニフェストのバージョンを取得します。</para>
        </summary>
        <value>
          <para>サービス マニフェスト バージョンです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />
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
            展開済みサービス パッケージの ActivationId を表す文字列。 場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>