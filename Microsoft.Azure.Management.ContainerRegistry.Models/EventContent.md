<Type Name="EventContent" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.EventContent">
  <TypeSignature Language="C#" Value="public class EventContent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventContent extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.EventContent" />
  <TypeSignature Language="VB.NET" Value="Public Class EventContent" />
  <TypeSignature Language="F#" Value="type EventContent = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            イベントの要求メッセージの内容。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventContent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            EventContent クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventContent (string id = null, Nullable&lt;DateTime&gt; timestamp = null, string action = null, Microsoft.Azure.Management.ContainerRegistry.Models.Target target = null, Microsoft.Azure.Management.ContainerRegistry.Models.Request request = null, Microsoft.Azure.Management.ContainerRegistry.Models.Actor actor = null, Microsoft.Azure.Management.ContainerRegistry.Models.Source source = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timestamp, string action, class Microsoft.Azure.Management.ContainerRegistry.Models.Target target, class Microsoft.Azure.Management.ContainerRegistry.Models.Request request, class Microsoft.Azure.Management.ContainerRegistry.Models.Actor actor, class Microsoft.Azure.Management.ContainerRegistry.Models.Source source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.#ctor(System.String,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Target,Microsoft.Azure.Management.ContainerRegistry.Models.Request,Microsoft.Azure.Management.ContainerRegistry.Models.Actor,Microsoft.Azure.Management.ContainerRegistry.Models.Source)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.EventContent : string * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.ContainerRegistry.Models.Target * Microsoft.Azure.Management.ContainerRegistry.Models.Request * Microsoft.Azure.Management.ContainerRegistry.Models.Actor * Microsoft.Azure.Management.ContainerRegistry.Models.Source -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.EventContent" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.EventContent (id, timestamp, action, target, request, actor, source)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="timestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="target" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Target" />
        <Parameter Name="request" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Request" />
        <Parameter Name="actor" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Actor" />
        <Parameter Name="source" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Source" />
      </Parameters>
      <Docs>
        <param name="id">イベント id。</param>
        <param name="timestamp">イベントが発生した時刻。</param>
        <param name="action">指定されたイベントを表すアクション。</param>
        <param name="target">イベントのターゲットです。</param>
        <param name="request">イベントを生成する要求。</param>
        <param name="actor">イベントを開始するエージェントです。 ほとんどの場合、要求の承認コンテキストから指定できます。</param>
        <param name="source">イベントを生成したレジストリ ノードです。
            ソースはアクターは、イベントが開始中には、put が異なりを生成します。</param>
        <summary>
            EventContent クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定されたイベントを表すアクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actor">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Actor Actor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Actor Actor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Actor" />
      <MemberSignature Language="VB.NET" Value="Public Property Actor As Actor" />
      <MemberSignature Language="F#" Value="member this.Actor : Microsoft.Azure.Management.ContainerRegistry.Models.Actor with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Actor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Actor</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベントを開始した、エージェントを設定します。 ほとんどの場合、要求の承認コンテキストから指定できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、イベント id です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Request Request { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Request Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Request" />
      <MemberSignature Language="VB.NET" Value="Public Property Request As Request" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Azure.Management.ContainerRegistry.Models.Request with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Request</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベントを生成した要求を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Source Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Source Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As Source" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.ContainerRegistry.Models.Source with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Source</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベントを生成したレジストリ ノードを設定します。 ソースはアクターは、イベントが開始中には、put が異なりを生成します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Target Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Target Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As Target" />
      <MemberSignature Language="F#" Value="member this.Target : Microsoft.Azure.Management.ContainerRegistry.Models.Target with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Target</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベントのターゲットを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Timestamp : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventContent.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベントが発生した時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>