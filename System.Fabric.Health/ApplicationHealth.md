<Type Name="ApplicationHealth" FullName="System.Fabric.Health.ApplicationHealth">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ApplicationHealth = class&#xA;    inherit EntityHealth" />
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
      <para>によって返されるアプリケーションの正常性を示します<see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealth.ApplicationName" />
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
    <Member MemberName="DeployedApplicationHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt; DeployedApplicationHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedApplicationHealthState&gt; DeployedApplicationHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.DeployedApplicationHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationHealthStates As IList(Of DeployedApplicationHealthState)" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt;" Usage="System.Fabric.Health.ApplicationHealth.DeployedApplicationHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Health store に検出されるように、現在のアプリケーションの展開済みアプリケーションの正常性状態を取得します。</para>
        </summary>
        <value>
          <para>health store に検出されるよう、現在のアプリケーション用のアプリケーションを展開します。</para>
        </value>
        <remarks>To be added.</remarks>
        <para>配置されているすべてのアプリケーションを評価して、アプリケーションで集計された正常性を決定します。</para>
        <para>考慮するアプリケーション展開のみ、 <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" /> (指定した場合) が返されます。 入力のフィルターが指定されていない場合は、配置されているすべてのアプリケーションが返されます。</para>
      </Docs>
    </Member>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.ApplicationHealth.HealthStatistics" />
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
            アプリケーションのエンティティの数が、に関する情報を含むアプリケーション ヘルス統計を取得<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            </summary>
        <value>アプリケーション状態の統計。</value>
        <remarks>
          <para>
            アプリケーションの正常性の統計情報がどのくらいサービス、パーティション、レプリカ、展開済みのアプリケーションに関する情報を格納し、展開済みサービス パッケージでは、 <see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            クエリを返す場合 null または空にすることできます、<see cref="T:System.Fabric.Health.ApplicationHealth" />指定<see cref="T:System.Fabric.Health.ApplicationHealthStatisticsFilter" />正常性の統計情報を除外します。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt; ServiceHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ServiceHealthState&gt; ServiceHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealth.ServiceHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHealthStates As IList(Of ServiceHealthState)" />
      <MemberSignature Language="F#" Value="member this.ServiceHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;" Usage="System.Fabric.Health.ApplicationHealth.ServiceHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Health store に検出されるように、現在のアプリケーションのサービスのヘルス状態を取得します。</para>
        </summary>
        <value>
          <para>Health store に検出されるよう、現在のアプリケーションのサービスです。</para>
        </value>
        <remarks>To be added.</remarks>
        <para>すべてのサービスを評価して、アプリケーションで集計された正常性を決定します。</para>
        <para>その点をサービスのみ、 <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" /> (指定した場合) が返されます。 入力のフィルターが指定されていない場合は、すべてのサービスが返されます。</para>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealth.ToString " />
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
            文字列表現を取得、<see cref="T:System.Fabric.Health.ApplicationHealth" />です。
            </summary>
        <returns><see cref="T:System.Fabric.Health.ApplicationHealth" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>