<Type Name="ProvisionApplicationTypeDescription" FullName="System.Fabric.Description.ProvisionApplicationTypeDescription">
  <TypeSignature Language="C#" Value="public sealed class ProvisionApplicationTypeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ProvisionApplicationTypeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ProvisionApplicationTypeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ProvisionApplicationTypeDescription" />
  <TypeSignature Language="F#" Value="type ProvisionApplicationTypeDescription = class" />
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
      <para>使用してプロビジョニングするアプリケーションの種類について説明します<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.Fabric.Description.ProvisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProvisionApplicationTypeDescription (string buildPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string buildPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ProvisionApplicationTypeDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (buildPath As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ProvisionApplicationTypeDescription : string -&gt; System.Fabric.Description.ProvisionApplicationTypeDescription" Usage="new System.Fabric.Description.ProvisionApplicationTypeDescription buildPath" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="buildPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="buildPath">
          <para>時に指定されたイメージ ストアにアプリケーション パッケージへの相対パス<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />です。</para>
        </param>
        <summary>
          <para>インスタンスをインスタンス化<see cref="T:System.Fabric.Description.ProvisionApplicationTypeDescription" />です。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Async">
      <MemberSignature Language="C#" Value="public bool Async { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Async" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ProvisionApplicationTypeDescription.Async" />
      <MemberSignature Language="VB.NET" Value="Public Property Async As Boolean" />
      <MemberSignature Language="F#" Value="member this.Async : bool with get, set" Usage="System.Fabric.Description.ProvisionApplicationTypeDescription.Async" />
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
          <para>取得または設定するかどうかを非同期的に発生する必要がありますプロビジョニングを示すフラグ。</para>
        </summary>
        <value>
          <para>かどうかは、このフラグが false の場合、動作は呼び出すことと同じ<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />です。 Timeout 引数は、プロビジョニング操作自体に適用され、システムでプロビジョニング操作が完了した場合にのみ、返されるタスクが完了します。</para>
          <para>このフラグが true、timeout 引数は、メッセージの配信にだけ適用し、返されるタスクが 1 回が完了した場合、システムに要求が許可しました。
            システムには、タイムアウトの制限がないプロビジョニング操作が処理されを使用して、状態を照会できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />です。
            使用して、保留中のプロビジョニング操作を中断できる<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String)" />です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildPath">
      <MemberSignature Language="C#" Value="public string BuildPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BuildPath" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ProvisionApplicationTypeDescription.BuildPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BuildPath As String" />
      <MemberSignature Language="F#" Value="member this.BuildPath : string" Usage="System.Fabric.Description.ProvisionApplicationTypeDescription.BuildPath" />
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
          <para>アプリケーション パッケージへの相対パスを取得中に指定されたイメージ ストアに<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />です。</para>
        </summary>
        <value>
          <para>アプリケーション パッケージのビルドのパス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>