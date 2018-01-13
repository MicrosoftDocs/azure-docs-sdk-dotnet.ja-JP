<Type Name="ServiceHealthQueryDescription" FullName="System.Fabric.Description.ServiceHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ServiceHealthQueryDescription = class" />
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
      <para>取得するためのクエリの入力を提供<see cref="T:System.Fabric.Health.ServiceHealth" />です。 <see cref="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription)" /> で使用されます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthQueryDescription (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceHealthQueryDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceHealthQueryDescription : Uri -&gt; System.Fabric.Description.ServiceHealthQueryDescription" Usage="new System.Fabric.Description.ServiceHealthQueryDescription serviceName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスの名前。 null にすることはできません。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Description.ServiceHealthQueryDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>Null 値は、必須パラメーターに渡されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ServiceHealthQueryDescription.EventsFilter" />
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
          <para>取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />サービスに報告します。 フィルターに一致するイベントのみが返されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.HealthEventsFilter" />返されるイベントをフィルター処理するために使用します。</para>
        </value>
        <remarks>
          <para> フィルターに一致するイベントのみが返されます。 すべてのイベントは、集計されたサービスのヘルス状態の評価に使用されます。
            フィルターが指定されていない場合は、すべてのイベントが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.ServiceHealthQueryDescription.HealthPolicy" />
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
          <para>取得または設定、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />正常性を評価するために使用します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />正常性を評価するために使用します。</para>
        </value>
        <remarks>指定されていない場合、正常性ストアは、サービスの正常性を評価する親アプリケーションのアプリケーションの正常性ポリシーを使用します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As ServiceHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.ServiceHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.ServiceHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または正常性の統計情報のフィルターを設定します。
            </summary>
        <value>正常性の統計情報のフィルターです。</value>
        <remarks>
          <para>
            正常性の統計情報のフィルター コントロールかどうか、<see cref="T:System.Fabric.Health.ServiceHealth" />によって返されるサービスの状態の統計がクエリに含まれています。 指定しない場合、統計情報が含まれます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.PartitionHealthStatesFilter PartitionsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.PartitionHealthStatesFilter PartitionsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceHealthQueryDescription.PartitionsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionsFilter As PartitionHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.PartitionsFilter : System.Fabric.Health.PartitionHealthStatesFilter with get, set" Usage="System.Fabric.Description.ServiceHealthQueryDescription.PartitionsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.PartitionHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>フィルター設定を取得または<see cref="T:System.Fabric.Health.PartitionHealthState" />子。 フィルターに一致する子のみが返されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.PartitionHealthStatesFilter" />返されるパーティションの正常性状態をフィルター処理するために使用します。</para>
        </value>
        <remarks>
          <para> フィルターに一致する子のみが返されます。 すべての子は、集計されたサービスのヘルス状態を評価する使用されます。
            フィルターが指定されていない場合は、パーティションのすべての子が返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" />
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
          <para>取得、<see cref="T:System.Uri" />サービス名。</para>
        </summary>
        <value>
          <para><see cref="T:System.Uri" />サービス名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthQueryDescription.ToString " />
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