<Type Name="DeployedServicePackageHealthState" FullName="System.Fabric.Health.DeployedServicePackageHealthState">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthState = class&#xA;    inherit EntityHealthState" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealthState</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>エンティティの識別子と、集計された正常性状態を含む、展開済みサービス パッケージのヘルス状態を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthState.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedServicePackageHealthState.ApplicationName" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthState.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedServicePackageHealthState.NodeName" />
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
          <para>展開済みサービス パッケージが実行されているノードのノードの名前を取得します。</para>
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthState.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Health.DeployedServicePackageHealthState.ServiceManifestName" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthState.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Health.DeployedServicePackageHealthState.ServicePackageActivationId" />
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
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthState.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            識別子と、集計された正常性状態を含む、展開済みサービス パッケージのヘルス状態の文字の説明を作成します。
            </summary>
        <returns>説明の文字列、<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>