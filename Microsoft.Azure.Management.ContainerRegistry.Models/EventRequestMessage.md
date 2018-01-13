<Type Name="EventRequestMessage" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage">
  <TypeSignature Language="C#" Value="public class EventRequestMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventRequestMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class EventRequestMessage" />
  <TypeSignature Language="F#" Value="type EventRequestMessage = class" />
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
            <span data-ttu-id="3bdf4-101">サービス URI に送信されるイベントの要求メッセージ。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-101">The event request message sent to the service URI.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventRequestMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3bdf4-102">EventRequestMessage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-102">Initializes a new instance of the EventRequestMessage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventRequestMessage (Microsoft.Azure.Management.ContainerRegistry.Models.EventContent content = null, System.Collections.Generic.IDictionary&lt;string,string&gt; headers = null, string method = null, string requestUri = null, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ContainerRegistry.Models.EventContent content, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; headers, string method, string requestUri, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.#ctor(Microsoft.Azure.Management.ContainerRegistry.Models.EventContent,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional content As EventContent = null, Optional headers As IDictionary(Of String, String) = null, Optional method As String = null, Optional requestUri As String = null, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage : Microsoft.Azure.Management.ContainerRegistry.Models.EventContent * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage (content, headers, method, requestUri, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="Microsoft.Azure.Management.ContainerRegistry.Models.EventContent" />
        <Parameter Name="headers" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="method" Type="System.String" />
        <Parameter Name="requestUri" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="3bdf4-103">イベントの要求メッセージの内容。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-103">The content of the event request message.</span></span></param>
        <param name="headers"><span data-ttu-id="3bdf4-104">イベントの要求メッセージのヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-104">The headers of the event request message.</span></span></param>
        <param name="method"><span data-ttu-id="3bdf4-105">イベントの要求メッセージを送信するために使用する HTTP メソッド。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-105">The HTTP method used to send the event request message.</span></span></param>
        <param name="requestUri"><span data-ttu-id="3bdf4-106">イベントの要求メッセージの送信に使用する URI。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-106">The URI used to send the event request message.</span></span></param>
        <param name="version"><span data-ttu-id="3bdf4-107">HTTP メッセージのバージョン。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-107">The HTTP message version.</span></span></param>
        <summary>
            <span data-ttu-id="3bdf4-108">EventRequestMessage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-108">Initializes a new instance of the EventRequestMessage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.EventContent Content { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.EventContent Content" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Content" />
      <MemberSignature Language="VB.NET" Value="Public Property Content As EventContent" />
      <MemberSignature Language="F#" Value="member this.Content : Microsoft.Azure.Management.ContainerRegistry.Models.EventContent with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Content" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="content")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.EventContent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bdf4-109">取得またはイベントの要求メッセージの内容を設定します。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-109">Gets or sets the content of the event request message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Headers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Headers" />
      <MemberSignature Language="VB.NET" Value="Public Property Headers As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="headers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bdf4-110">取得またはイベントの要求メッセージのヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-110">Gets or sets the headers of the event request message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Method">
      <MemberSignature Language="C#" Value="public string Method { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Method" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Method" />
      <MemberSignature Language="VB.NET" Value="Public Property Method As String" />
      <MemberSignature Language="F#" Value="member this.Method : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Method" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="method")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bdf4-111">取得またはイベントの要求メッセージの送信に使用される HTTP メソッドを設定します。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-111">Gets or sets the HTTP method used to send the event request message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestUri">
      <MemberSignature Language="C#" Value="public string RequestUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.RequestUri" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestUri As String" />
      <MemberSignature Language="F#" Value="member this.RequestUri : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.RequestUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requestUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bdf4-112">取得またはイベントの要求メッセージの送信に使用する URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-112">Gets or sets the URI used to send the event request message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bdf4-113">HTTP メッセージ バージョンを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="3bdf4-113">Gets or sets the HTTP message version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>