<Type Name="ApplicationHealthQueryDescription" FullName="System.Fabric.Description.ApplicationHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ApplicationHealthQueryDescription = class" />
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
      <para>アプリケーションの正常性を取得するためのクエリの入力を表します。 <see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" /> で使用されます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthQueryDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationHealthQueryDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationHealthQueryDescription : Uri -&gt; System.Fabric.Description.ApplicationHealthQueryDescription" Usage="new System.Fabric.Description.ApplicationHealthQueryDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション名。 ことはできません<languageKeyword>null</languageKeyword>です。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>Null 値は、必須パラメーターに渡されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />
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
    <Member MemberName="DeployedApplicationsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStatesFilter DeployedApplicationsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStatesFilter DeployedApplicationsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeployedApplicationsFilter As DeployedApplicationHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationsFilter : System.Fabric.Health.DeployedApplicationHealthStatesFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>フィルター設定を取得または<see cref="T:System.Fabric.Health.DeployedApplicationHealthState" />子。 フィルターに一致する子のみが返されます。 すべての子は、アプリケーションで集計された正常性状態の評価に使用されます。</para>
        </summary>
        <value>
          <para>フィルター<see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" />子。</para>
        </value>
        <remarks>
          <para> フィルターに一致する子のみが返されます。 すべての子は、アプリケーションで集計された正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、アプリケーションの展開済みアプリケーションのすべての子が返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.EventsFilter" />
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
          <para>取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />のアプリケーションに報告します。 フィルターに一致するイベントのみが返されます。 すべてのイベントは、アプリケーションで集計された正常性状態の評価に使用されます。</para>
        </summary>
        <value>
          <para>コレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />のアプリケーションに報告します。</para>
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.HealthPolicy" />
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
          <para>取得または設定、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />アプリケーションの正常性を評価するために使用します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />アプリケーションの正常性を評価するために使用します。</para>
        </value>
        <remarks>指定しない場合、正常性ストアは、アプリケーションを評価する、アプリケーション マニフェストで指定されたアプリケーションの正常性ポリシーを使用します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As ApplicationHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.ApplicationHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または正常性の統計情報のフィルターを設定します。
            </summary>
        <value>正常性の統計情報のフィルターです。</value>
        <remarks>
          <para>
            正常性の統計情報のフィルター コントロールかどうか、<see cref="T:System.Fabric.Health.ApplicationHealth" />によって返される、クエリには、アプリケーションの正常性の統計情報が含まれています。 指定しない場合、統計情報が含まれます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthStatesFilter ServicesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthStatesFilter ServicesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicesFilter As ServiceHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ServicesFilter : System.Fabric.Health.ServiceHealthStatesFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>フィルター設定を取得または<see cref="T:System.Fabric.Health.ServiceHealthState" />子。 フィルターに一致する子のみが返されます。 すべての子は、アプリケーションで集計された正常性状態の評価に使用されます。</para>
        </summary>
        <value>
          <para>フィルター<see cref="T:System.Fabric.Health.ServiceHealthState" />子。</para>
        </value>
        <remarks>
          <para> フィルターに一致する子のみが返されます。 すべての子は、アプリケーションで集計された正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、アプリケーションのサービスのすべての子が返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthQueryDescription.ToString " />
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