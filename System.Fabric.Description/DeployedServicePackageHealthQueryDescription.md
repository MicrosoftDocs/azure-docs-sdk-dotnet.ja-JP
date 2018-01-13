<Type Name="DeployedServicePackageHealthQueryDescription" FullName="System.Fabric.Description.DeployedServicePackageHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthQueryDescription = class" />
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
      <para>説明を取得するクエリの入力<see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />です。 <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" /> で使用されます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthQueryDescription (Uri applicationName, string nodeName, string serviceManifestName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName, string serviceManifestName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.#ctor(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String, serviceManifestName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription : Uri * string * string -&gt; System.Fabric.Description.DeployedServicePackageHealthQueryDescription" Usage="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription (applicationName, nodeName, serviceManifestName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション名。 null にすることはできません。</para>
        </param>
        <param name="nodeName">
          <para>ノード名。 null または空にすることはできません。</para>
        </param>
        <param name="serviceManifestName">
          <para>サービス マニフェスト名です。 null または空にすることはできません。</para>
        </param>
        <summary>
          <para>インスタンスを作成、<see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />クラスです。</para>
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
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthQueryDescription (Uri applicationName, string nodeName, string serviceManifestName, string servicePackageActivationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName, string serviceManifestName, string servicePackageActivationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.#ctor(System.Uri,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String, serviceManifestName As String, servicePackageActivationId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription : Uri * string * string * string -&gt; System.Fabric.Description.DeployedServicePackageHealthQueryDescription" Usage="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription (applicationName, nodeName, serviceManifestName, servicePackageActivationId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション名。 null にすることはできません。</para>
        </param>
        <param name="nodeName">
          <para>ノード名。 null または空にすることはできません。</para>
        </param>
        <param name="serviceManifestName">
          <para>サービス マニフェスト名です。 null または空にすることはできません。</para>
        </param>
        <param name="servicePackageActivationId">
          <para>
            <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービス パッケージのです。
            使用して取得できます、展開済みサービス パッケージの ServicePackageActivationId<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。 
            </para>
          <para>
            場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
        </param>
        <summary>
          <para>インスタンスを作成、<see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />クラスです。</para>
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />
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
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.EventsFilter" />
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
          <para>取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />展開済みサービス パッケージに報告します。 フィルターに一致するイベントのみが返されます。 すべてのイベントは、集計された正常性状態の評価に使用されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.HealthEventsFilter" />返されるイベントをフィルター処理するために使用します。</para>
        </value>
        <remarks>
          <para> フィルターに一致するイベントのみが返されます。 すべてのイベントは、エンティティで集計された正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、すべてのイベントが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.HealthPolicy" />
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
        <remarks>指定されていない場合、正常性ストアは、展開済みサービス パッケージの正常性を評価する親アプリケーションのアプリケーションの正常性ポリシーを使用します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.NodeName" />
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
          <para><see cref="T:System.String" />ノード名を表すです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServiceManifestName" />
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
          <para><see cref="T:System.String" />サービス マニフェスト名を表すです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServicePackageActivationId" />
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
            <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービス パッケージのです。 使用して取得できます、展開済みサービス パッケージの ServicePackageActivationId<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。 
            </para>
          <para>
            場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。 
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthQueryDescription.ToString " />
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