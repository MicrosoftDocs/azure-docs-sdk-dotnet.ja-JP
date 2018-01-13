<Type Name="ClusterManifestQueryDescription" FullName="System.Fabric.Description.ClusterManifestQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ClusterManifestQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterManifestQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ClusterManifestQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterManifestQueryDescription" />
  <TypeSignature Language="F#" Value="type ClusterManifestQueryDescription = class" />
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
            使用するクエリ パラメーターについて説明します<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync(System.Fabric.Description.ClusterManifestQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterManifestQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterManifestQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            コンストラクトは、クラスター マニフェストの内容を取得するためのパラメーターをクエリします。
            </para>
        </summary>
        <remarks>
          <para>
            既定では、現在の実行中のクラスター マニフェストが取得されます。 以前を使用してプロビジョニングされた別のクラスター マニフェスト バージョンを照会する<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ProvisionFabricAsync(System.String,System.String)" />、目的のクエリのバージョンを使用して、指定<see cref="P:System.Fabric.Description.ClusterManifestQueryDescription.ClusterManifestVersion" />です。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterManifestVersion">
      <MemberSignature Language="C#" Value="public string ClusterManifestVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterManifestVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterManifestQueryDescription.ClusterManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterManifestVersion As String" />
      <MemberSignature Language="F#" Value="member this.ClusterManifestVersion : string with get, set" Usage="System.Fabric.Description.ClusterManifestQueryDescription.ClusterManifestVersion" />
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
          <para>
            取得または設定を取得するクラスター マニフェストのバージョン。
            </para>
        </summary>
        <value>
          <para>クラスター マニフェストのバージョン。</para>
        </value>
        <remarks>
          <para>
            Null (既定値) または空の文字列に設定すると、現在の実行中のクラスター マニフェストが取得されます。
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>