<Type Name="EventHubsConnectionStringBuilder" FullName="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class EventHubsConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubsConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubsConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type EventHubsConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            EventHubsConnectionStringBuilder は、Event Hubs のエンティティとの通信を確立できる接続文字列を構築するために使用できます。
            既存の接続文字列で基本的な検証を実行するも使用できます。
            <para />接続文字列は、基本的に、文字列で区切られたキーと値のペアで構成されている「;」です。 基本形式は"&lt;キー&gt;=&lt;値&gt;[;&lt;キー&gt;=&lt;値&gt;]"サポートされているキー名が次のような場所:<para />エンドポイントにイベント ハブ名前空間を含む URL <para /> EntityPath - Event Hub へのパスエンティティ<para />SharedAccessKeyName - 名前空間、またはエンティティの対応する共有アクセス ポリシーのルールにキーの名前。
            <para />SharedAccessKey -、対応する共有アクセス ポリシー規則の名前空間またはエンティティのキー。
            </summary>
    <remarks>To be added.</remarks>
    <example>
            サンプル コード: 
            <code>
            var connectionStringBuiler = new EventHubsConnectionStringBuilder(
                "amqps://EventHubsNamespaceName.servicebus.windows.net", 
                "EventHubsEntityName", // Event Hub Name 
                "SharedAccessSignatureKeyName", 
                "SharedAccessSignatureKey");
             string connectionString = connectionStringBuiler.ToString();
            </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : string -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">イベント ハブの接続文字列</param>
        <summary>
            ConnectionString の形式: エンドポイント = sb://namespace_DNS_Name です。EntityPath EVENT_HUB_NAME; を =SharedAccessKeyName = SHARED_ACCESS_KEY_NAME です。SharedAccessKey SHARED_ACCESS_KEY を =
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessKeyName As String, sharedAccessKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * string -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessKeyName, sharedAccessKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="entityPath">エンティティのパスまたは Event Hub の名前。</param>
        <param name="sharedAccessKeyName">共有アクセス キーの名前</param>
        <param name="sharedAccessKey">共有アクセス キー</param>
        <summary>
            使用できる接続文字列を作成します。<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessSignature, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessSignature, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessSignature As String, operationTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * TimeSpan -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessSignature, operationTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessSignature" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="entityPath">エンティティのパスまたは Event Hub の名前。</param>
        <param name="sharedAccessSignature">Shared Access Signature</param>
        <param name="operationTimeout">Event Hubs の操作の操作のタイムアウト</param>
        <summary>
            使用できる接続文字列を作成します。<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessKeyName As String, sharedAccessKey As String, operationTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * string * TimeSpan -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessKeyName, sharedAccessKey, operationTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Event Hubs の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="entityPath">エンティティのパスまたは Event Hub の名前。</param>
        <param name="sharedAccessKeyName">共有アクセス キーの名前</param>
        <param name="sharedAccessKey">共有アクセス キー</param>
        <param name="operationTimeout">Event Hubs の操作の操作のタイムアウト</param>
        <summary>
            使用できる接続文字列を作成します。<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As EventHubsConnectionStringBuilder" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="eventHubsConnectionStringBuilder.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のオブジェクトのクローンを作成<see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" />です。
            </summary>
        <returns>新しい<see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" /></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public Uri Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.Endpoint : Uri with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Event Hubs のエンドポイントを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            接続文字列からエンティティ path の値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            関連するについて、呼び出し元に通知するエラーがある状況で OperationTimeout が適用されます。<see cref="T:Microsoft.Azure.EventHubs.EventHubsException" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKey">
      <MemberSignature Language="C#" Value="public string SasKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKey As String" />
      <MemberSignature Language="F#" Value="member this.SasKey : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            接続文字列からの共有アクセス ポリシー キーの値を取得します。
            </summary>
        <value>共有アクセス署名キー</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKeyName">
      <MemberSignature Language="C#" Value="public string SasKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SasKeyName : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            接続文字列から、共有アクセス ポリシーの所有者名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public string SharedAccessSignature { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessSignature As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または SAS アクセス トークンを設定します。
            </summary>
        <value>Shared Access Signature</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="eventHubsConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            イベント ハブ Namespace への接続に使用できる相互操作可能な接続文字列を返します
            </summary>
        <returns>接続文字列</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.TransportType TransportType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.EventHubs.TransportType TransportType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.TransportType" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportType As TransportType" />
      <MemberSignature Language="F#" Value="member this.TransportType : Microsoft.Azure.EventHubs.TransportType with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.TransportType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TransportType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トランスポートのクライアント接続の種類。
            使用可能なオプションは、Amqp AmqpWebSockets です。
            Amqp が指定されていない場合に既定値です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>