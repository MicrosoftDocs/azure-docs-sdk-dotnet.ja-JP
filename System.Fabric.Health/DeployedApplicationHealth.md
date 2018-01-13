<Type Name="DeployedApplicationHealth" FullName="System.Fabric.Health.DeployedApplicationHealth">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>によって返されるノードにデプロイされたアプリケーションの正常性について説明します<see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealth.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedApplicationHealth.ApplicationName" />
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
          <para>アプリケーションを一意に識別するアプリケーション名を取得します。 </para>
        </summary>
        <value>
          <para>アプリケーション名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServicePackageHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt; DeployedServicePackageHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedServicePackageHealthState&gt; DeployedServicePackageHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealth.DeployedServicePackageHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServicePackageHealthStates As IList(Of DeployedServicePackageHealthState)" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackageHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;" Usage="System.Fabric.Health.DeployedApplicationHealth.DeployedServicePackageHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Health store に、検出されるよう、現在の展開済みアプリケーションの展開済みサービス パッケージの正常性状態を取得します。</para>
        </summary>
        <value>
          <para>現在展開済みアプリケーションの展開済みサービス パッケージは、health store に見つかりました。</para>
        </value>
        <remarks>To be added.</remarks>
        <para>すべての展開済みサービス パッケージを評価して、展開されたアプリケーションで集計された正常性を決定します。</para>
        <para>サービスの展開のみがその点をパッケージ化、 <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" /> (指定した場合) が返されます。 入力のフィルターが指定されていない場合は、すべての展開済みサービス パッケージが返されます。</para>
      </Docs>
    </Member>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.DeployedApplicationHealth.HealthStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            展開済みサービス パッケージの数が、に関する情報を含む展開済みアプリケーション ヘルス統計を取得<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            </summary>
        <value>展開済みアプリケーション正常性の統計。</value>
        <remarks>
          <para>
            展開済みアプリケーションの稼働状態の統計情報には展開済みサービス パッケージの数が、 <see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            クエリを返す場合 null または空にすることできます、<see cref="T:System.Fabric.Health.DeployedApplicationHealth" />指定<see cref="T:System.Fabric.Health.DeployedApplicationHealthStatisticsFilter" />正常性の統計情報を除外します。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealth.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedApplicationHealth.NodeName" />
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
          <para>アプリケーションが配置されているノードのノード名を取得します。</para>
        </summary>
        <value>
          <para>アプリケーションが配置されているノードのノード名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealth.ToString " />
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
            文字列表現を取得、<see cref="T:System.Fabric.Health.DeployedApplicationHealth" />です。
            </summary>
        <returns><see cref="T:System.Fabric.Health.DeployedApplicationHealth" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>