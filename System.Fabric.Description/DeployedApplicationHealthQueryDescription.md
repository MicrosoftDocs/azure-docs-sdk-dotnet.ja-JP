<Type Name="DeployedApplicationHealthQueryDescription" FullName="System.Fabric.Description.DeployedApplicationHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthQueryDescription = class" />
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
      <para>説明を取得するためのクエリ入力<see cref="T:System.Fabric.Health.DeployedApplicationHealth" />です。 <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" /> で使用されます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthQueryDescription (Uri applicationName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedApplicationHealthQueryDescription.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedApplicationHealthQueryDescription : Uri * string -&gt; System.Fabric.Description.DeployedApplicationHealthQueryDescription" Usage="new System.Fabric.Description.DeployedApplicationHealthQueryDescription (applicationName, nodeName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション名。 null にすることはできません。</para>
        </param>
        <param name="nodeName">
          <para>ノード名。 null または空にすることはできません。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>必須のパラメーターを null にすることはできません。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>必須のパラメーターを空にすることはできません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />
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
          <para>アプリケーションの名前です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServicePackagesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedServicePackageHealthStatesFilter DeployedServicePackagesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedServicePackageHealthStatesFilter DeployedServicePackagesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeployedServicePackagesFilter As DeployedServicePackageHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackagesFilter : System.Fabric.Health.DeployedServicePackageHealthStatesFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedServicePackageHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>フィルター設定を取得または<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />子。 フィルターに一致する子のみが返されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" />返された展開済みサービス パッケージをフィルター処理するために使用します。</para>
        </value>
        <remarks>
          <para> フィルターに一致する子のみが返されます。 すべての子は、展開されたアプリケーションで集計された正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、展開済みアプリケーションの展開済みサービス パッケージのすべての子が返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.EventsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEventsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />配置したアプリケーションで報告します。 フィルターに一致するイベントのみが返されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.HealthEventsFilter" />返されるイベントをフィルター処理するために使用します。</para>
        </value>
        <remarks>
          <para> フィルターに一致するイベントのみが返されます。 すべてのイベントは、アプリケーションで集計された正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、すべてのイベントが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />展開済みアプリケーションの正常性を評価するために使用します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />正常性を評価するために使用します。</para>
        </value>
        <remarks>指定しない場合、正常性ストアは、アプリケーションの正常性ポリシーまたは親アプリケーション、展開されたアプリケーションを評価します。
            アプリケーションの正常性ポリシーは、アプリケーション マニフェストで指定されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As DeployedApplicationHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.DeployedApplicationHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または正常性の統計情報のフィルターを設定します。
            </summary>
        <value>正常性の統計情報のフィルターです。</value>
        <remarks>
          <para>
            正常性の統計情報のフィルター コントロールかどうか、<see cref="T:System.Fabric.Health.DeployedApplicationHealth" />によって返される、クエリには、展開済みアプリケーション正常性の統計情報が含まれています。 指定しない場合、統計情報が含まれます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.NodeName" />
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
          <para>ノード名を取得します。</para>
        </summary>
        <value>
          <para>ノード名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthQueryDescription.ToString " />
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
            正常性クエリの説明の文字列表現を取得します。
            </summary>
        <returns>正常性クエリの説明の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>