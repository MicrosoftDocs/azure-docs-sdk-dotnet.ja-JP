<Type Name="ResizeError" FullName="Microsoft.Azure.Management.Batch.Models.ResizeError">
  <TypeSignature Language="C#" Value="public class ResizeError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResizeError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ResizeError" />
  <TypeSignature Language="VB.NET" Value="Public Class ResizeError" />
  <TypeSignature Language="F#" Value="type ResizeError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="03c7f-101">プールのサイズを変更するときに発生したエラーです。</span><span class="sxs-lookup"><span data-stu-id="03c7f-101">An error that occurred when resizing a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResizeError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ResizeError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="03c7f-102">ResizeError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="03c7f-102">Initializes a new instance of the ResizeError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResizeError (string code, string message, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ResizeError&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ResizeError.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.ResizeError})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (code As String, message As String, Optional details As IList(Of ResizeError) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ResizeError : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt; -&gt; Microsoft.Azure.Management.Batch.Models.ResizeError" Usage="new Microsoft.Azure.Management.Batch.Models.ResizeError (code, message, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="03c7f-103">エラーの識別子。</span><span class="sxs-lookup"><span data-stu-id="03c7f-103">An identifier for the error.</span></span> <span data-ttu-id="03c7f-104">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="03c7f-104">Codes are invariant and are intended to be consumed programmatically.</span></span></param>
        <param name="message"><span data-ttu-id="03c7f-105">ユーザー インターフェイスでの表示に適したするもので、エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="03c7f-105">A message describing the error, intended to be suitable for display in a user interface.</span></span></param>
        <param name="details"><span data-ttu-id="03c7f-106">エラーの詳細を追加します。</span><span class="sxs-lookup"><span data-stu-id="03c7f-106">Additional details about the error.</span></span></param>
        <summary>
            <span data-ttu-id="03c7f-107">ResizeError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="03c7f-107">Initializes a new instance of the ResizeError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ResizeError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ResizeError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="03c7f-108">取得または設定エラーの識別子。</span><span class="sxs-lookup"><span data-stu-id="03c7f-108">Gets or sets an identifier for the error.</span></span> <span data-ttu-id="03c7f-109">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="03c7f-109">Codes are invariant and are intended to be consumed programmatically.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ResizeError&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ResizeError.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of ResizeError)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ResizeError.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03c7f-110">取得またはエラーに関する追加情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="03c7f-110">Gets or sets additional details about the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ResizeError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ResizeError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="03c7f-111">取得または設定するユーザー インターフェイスでの表示に適したもので、エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="03c7f-111">Gets or sets a message describing the error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ResizeError.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resizeError.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="03c7f-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="03c7f-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03c7f-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03c7f-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>