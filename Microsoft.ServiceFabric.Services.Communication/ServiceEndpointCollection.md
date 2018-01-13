<Type Name="ServiceEndpointCollection" FullName="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection">
  <TypeSignature Language="C#" Value="public sealed class ServiceEndpointCollection" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceEndpointCollection extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceEndpointCollection" />
  <TypeSignature Language="F#" Value="type ServiceEndpointCollection = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            このクラスは、信頼性の高いサービスのエンドポイントを表します。 各エンドポイントには、リスナーの名前とそのリスナーのアドレスがあります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceEndpointCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            空の ServiceEndpointsCollection をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceEndpointCollection (string listenerName, string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string listenerName, string endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (listenerName As String, endpointAddress As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection : string * string -&gt; Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection" Usage="new Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection (listenerName, endpointAddress)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="endpointAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="listenerName">エンドポイントのリスナーの名前</param>
        <param name="endpointAddress">エンドポイントのアドレス</param>
        <summary>
            リスナー名で識別される、単一のエンドポイントと ServiceEndpointsCollection をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddEndpoint">
      <MemberSignature Language="C#" Value="public void AddEndpoint (string listenerName, string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddEndpoint(string listenerName, string endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.AddEndpoint(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddEndpoint (listenerName As String, endpointAddress As String)" />
      <MemberSignature Language="F#" Value="member this.AddEndpoint : string * string -&gt; unit" Usage="serviceEndpointCollection.AddEndpoint (listenerName, endpointAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="endpointAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="listenerName">エンドポイントのリスナーの名前</param>
        <param name="endpointAddress">エンドポイントのアドレス</param>
        <summary>
            EndpointsCollection にエンドポイントを追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddEndpoints">
      <MemberSignature Language="C#" Value="public void AddEndpoints (Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection newEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddEndpoints(class Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection newEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.AddEndpoints(Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddEndpoints (newEndpoints As ServiceEndpointCollection)" />
      <MemberSignature Language="F#" Value="member this.AddEndpoints : Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection -&gt; unit" Usage="serviceEndpointCollection.AddEndpoints newEndpoints" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newEndpoints" Type="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection" />
      </Parameters>
      <Docs>
        <param name="newEndpoints">入力 EndpointsCollection</param>
        <summary>
            入力の EndpointsCollection クラスで、EndpointsCollection にエンドポイントを追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToReadOnlyDictionary">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; ToReadOnlyDictionary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; ToReadOnlyDictionary() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.ToReadOnlyDictionary" />
      <MemberSignature Language="VB.NET" Value="Public Function ToReadOnlyDictionary () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.ToReadOnlyDictionary : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="serviceEndpointCollection.ToReadOnlyDictionary " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            EndpointsCollection ReadOnlyDictionary を返します。
            </summary>
        <returns>ReadOnlyDictionary として EndpointsCollection</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceEndpointCollection.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            フォームの JSON 文字列に変換する、endpointsCollection {「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}
            </summary>
        <returns>文字列形式、endpointsCollection</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetEndpointAddress">
      <MemberSignature Language="C#" Value="public bool TryGetEndpointAddress (string listenerName, out string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetEndpointAddress(string listenerName, [out] string&amp; endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryGetEndpointAddress(System.String,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetEndpointAddress (listenerName As String, ByRef endpointAddress As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetEndpointAddress : string *  -&gt; bool" Usage="serviceEndpointCollection.TryGetEndpointAddress (listenerName, endpointAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="endpointAddress" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="listenerName">リスナー名</param>
        <param name="endpointAddress">そのリスナーの名前を持つエンドポイントが存在する場合のエンドポイントのアドレス。</param>
        <summary>
            リスナー名で識別されるエンドポイントを取得します。
            </summary>
        <returns>リスナー名を持つエンドポイントが存在するそれ以外の場合は、true を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetFirstEndpointAddress">
      <MemberSignature Language="C#" Value="public bool TryGetFirstEndpointAddress (out string endpointAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetFirstEndpointAddress([out] string&amp; endpointAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryGetFirstEndpointAddress(System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetFirstEndpointAddress (ByRef endpointAddress As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetFirstEndpointAddress :  -&gt; bool" Usage="serviceEndpointCollection.TryGetFirstEndpointAddress endpointAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">最初のエンドポイント、EndpointsCollection で</param>
        <summary>
            EndpointsCollection 内の最初のエンドポイント アドレスを取得します。
            </summary>
        <returns>ある場合に少なくとも 1 つのエンドポイント、EndpointsCollection false それ以外の場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParseEndpointsString">
      <MemberSignature Language="C#" Value="public static bool TryParseEndpointsString (string endpointsString, out Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection serviceEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryParseEndpointsString(string endpointsString, [out] class Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection&amp; serviceEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryParseEndpointsString(System.String,Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryParseEndpointsString (endpointsString As String, ByRef serviceEndpoints As ServiceEndpointCollection) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryParseEndpointsString : string *  -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection.TryParseEndpointsString (endpointsString, serviceEndpoints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointsString" Type="System.String" />
        <Parameter Name="serviceEndpoints" Type="Microsoft.ServiceFabric.Services.Communication.ServiceEndpointCollection&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="endpointsString">endpointsCollection の文字列の形式</param>
        <param name="serviceEndpoints">有効な ServiceEndpointCollection オブジェクトを文字列を解析できる場合は、ServiceEndpointCollection オブジェクト</param>
        <summary>
            エンドポイントの文字列バージョンから、EndpointsCollection を構築します。 EndpointsCollection の文字列形式がの形式が {「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}
            </summary>
        <returns>文字列をそれ以外の場合、有効な EndpointsCollection、False を解析できる場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>