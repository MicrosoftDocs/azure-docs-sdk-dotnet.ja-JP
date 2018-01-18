<Type Name="ResponseMessage" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage">
  <TypeSignature Language="C#" Value="public class ResponseMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResponseMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class ResponseMessage" />
  <TypeSignature Language="F#" Value="type ResponseMessage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ResponseMessage", Namespace="urn:ServiceFabric.Communication")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="82879-101">これは、wcf のリモート処理中に受信した応答を表します。</span><span class="sxs-lookup"><span data-stu-id="82879-101">This represent response received during wcf remoting.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResponseMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="82879-102">空のヘッダーと本文の応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="82879-102">Creates Response with Empty Headers and Body</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageHeaders">
      <MemberSignature Language="C#" Value="public ArraySegment&lt;byte&gt; MessageHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ArraySegment`1&lt;unsigned int8&gt; MessageHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage.MessageHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageHeaders As ArraySegment(Of Byte)" />
      <MemberSignature Language="F#" Value="member this.MessageHeaders : ArraySegment&lt;byte&gt; with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage.MessageHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="Headers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ArraySegment&lt;System.Byte&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82879-103">応答メッセージにヘッダー</span><span class="sxs-lookup"><span data-stu-id="82879-103">Headers in the response Message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseBody">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; ResponseBody { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; ResponseBody" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage.ResponseBody" />
      <MemberSignature Language="VB.NET" Value="Public Property ResponseBody As IEnumerable(Of ArraySegment(Of Byte))" />
      <MemberSignature Language="F#" Value="member this.ResponseBody : seq&lt;ArraySegment&lt;byte&gt;&gt; with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage.ResponseBody" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="ResponseBody")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82879-104">応答メッセージにメッセージ本文</span><span class="sxs-lookup"><span data-stu-id="82879-104">Message body in the response Message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>