<Type Name="BatchAIError" FullName="Microsoft.Azure.Management.BatchAI.Models.BatchAIError">
  <TypeSignature Language="C#" Value="public class BatchAIError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAIError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.BatchAIError" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAIError" />
  <TypeSignature Language="F#" Value="type BatchAIError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="28aac-101">バッチ AI サービスからのエラー応答。</span><span class="sxs-lookup"><span data-stu-id="28aac-101">An error response from the Batch AI service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAIError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.BatchAIError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="28aac-102">BatchAIError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="28aac-102">Initializes a new instance of the BatchAIError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAIError (string code = null, string message = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.NameValuePair&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.NameValuePair&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.BatchAIError.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.NameValuePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional details As IList(Of NameValuePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.BatchAIError : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.NameValuePair&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.BatchAIError" Usage="new Microsoft.Azure.Management.BatchAI.Models.BatchAIError (code, message, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.NameValuePair&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="28aac-103">エラーの識別子。</span><span class="sxs-lookup"><span data-stu-id="28aac-103">An identifier for the error.</span></span> <span data-ttu-id="28aac-104">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="28aac-104">Codes are invariant and are intended to be consumed programmatically.</span></span></param>
        <param name="message"><span data-ttu-id="28aac-105">ユーザー インターフェイスでの表示に適したするもので、エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="28aac-105">A message describing the error, intended to be suitable for display in a user interface.</span></span></param>
        <param name="details"><span data-ttu-id="28aac-106">エラーに関する追加情報の一覧。</span><span class="sxs-lookup"><span data-stu-id="28aac-106">A list of additional details about the error.</span></span></param>
        <summary>
            <span data-ttu-id="28aac-107">BatchAIError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="28aac-107">Initializes a new instance of the BatchAIError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.BatchAIError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.BatchAIError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="28aac-108">取得または設定エラーの識別子。</span><span class="sxs-lookup"><span data-stu-id="28aac-108">Gets or sets an identifier for the error.</span></span> <span data-ttu-id="28aac-109">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="28aac-109">Codes are invariant and are intended to be consumed programmatically.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.NameValuePair&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.NameValuePair&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.BatchAIError.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.BatchAIError.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="28aac-110">取得またはエラーに関する追加情報の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="28aac-110">Gets or sets a list of additional details about the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.BatchAIError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.BatchAIError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="28aac-111">取得または設定するユーザー インターフェイスでの表示に適したもので、エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="28aac-111">Gets or sets a message describing the error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>