<Type Name="ComputeNodeError" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError">
  <TypeSignature Language="C#" Value="public class ComputeNodeError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeError" />
  <TypeSignature Language="F#" Value="type ComputeNodeError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="940cc-101">コンピューティング ノードで発生したエラーです。</span><span class="sxs-lookup"><span data-stu-id="940cc-101">An error encountered by a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="940cc-102">ComputeNodeError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="940cc-102">Initializes a new instance of the ComputeNodeError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeError (string code = null, string message = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; errorDetails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; errorDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.NameValuePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional errorDetails As IList(Of NameValuePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError (code, message, errorDetails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="940cc-103">コンピューティング ノードのエラーの識別子。</span><span class="sxs-lookup"><span data-stu-id="940cc-103">An identifier for the compute node error.</span></span> <span data-ttu-id="940cc-104">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="940cc-104">Codes are invariant and are intended to be consumed programmatically.</span></span></param>
        <param name="message"><span data-ttu-id="940cc-105">ユーザー インターフェイスでの表示に適したするもので、コンピューティング ノードのエラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="940cc-105">A message describing the compute node error, intended to be suitable for display in a user interface.</span></span></param>
        <param name="errorDetails"><span data-ttu-id="940cc-106">コンピューティング ノードのエラーに関連する追加のエラー詳細の一覧。</span><span class="sxs-lookup"><span data-stu-id="940cc-106">The list of additional error details related to the compute node error.</span></span></param>
        <summary>
            <span data-ttu-id="940cc-107">ComputeNodeError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="940cc-107">Initializes a new instance of the ComputeNodeError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="940cc-108">取得またはコンピューティング ノードのエラーの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="940cc-108">Gets or sets an identifier for the compute node error.</span></span> <span data-ttu-id="940cc-109">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="940cc-109">Codes are invariant and are intended to be consumed programmatically.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; ErrorDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorDetails As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.ErrorDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="940cc-110">取得またはコンピューティング ノードのエラーに関連する追加のエラーの詳細の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="940cc-110">Gets or sets the list of additional error details related to the compute node error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="940cc-111">取得または設定するユーザー インターフェイスでの表示に適したもので、コンピューティング ノードのエラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="940cc-111">Gets or sets a message describing the compute node error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>