<Type Name="DeleteCertificateError" FullName="Microsoft.Azure.Management.Batch.Models.DeleteCertificateError">
  <TypeSignature Language="C#" Value="public class DeleteCertificateError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeleteCertificateError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.DeleteCertificateError" />
  <TypeSignature Language="VB.NET" Value="Public Class DeleteCertificateError" />
  <TypeSignature Language="F#" Value="type DeleteCertificateError = class" />
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
            <span data-ttu-id="07cb9-101">バッチ サービスからのエラー応答。</span><span class="sxs-lookup"><span data-stu-id="07cb9-101">An error response from the Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeleteCertificateError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07cb9-102">DeleteCertificateError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="07cb9-102">Initializes a new instance of the DeleteCertificateError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeleteCertificateError (string code, string message, string target = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DeleteCertificateError&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, string target, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.DeleteCertificateError&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.DeleteCertificateError})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (code As String, message As String, Optional target As String = null, Optional details As IList(Of DeleteCertificateError) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.DeleteCertificateError : string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DeleteCertificateError&gt; -&gt; Microsoft.Azure.Management.Batch.Models.DeleteCertificateError" Usage="new Microsoft.Azure.Management.Batch.Models.DeleteCertificateError (code, message, target, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DeleteCertificateError&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="07cb9-103">エラーの識別子。</span><span class="sxs-lookup"><span data-stu-id="07cb9-103">An identifier for the error.</span></span> <span data-ttu-id="07cb9-104">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="07cb9-104">Codes are invariant and are intended to be consumed programmatically.</span></span></param>
        <param name="message"><span data-ttu-id="07cb9-105">ユーザー インターフェイスでの表示に適したするもので、エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="07cb9-105">A message describing the error, intended to be suitable for display in a user interface.</span></span></param>
        <param name="target"><span data-ttu-id="07cb9-106">特定のエラーのターゲットです。</span><span class="sxs-lookup"><span data-stu-id="07cb9-106">The target of the particular error.</span></span> <span data-ttu-id="07cb9-107">たとえば、エラー プロパティの名前です。</span><span class="sxs-lookup"><span data-stu-id="07cb9-107">For example, the name of the property in error.</span></span></param>
        <param name="details"><span data-ttu-id="07cb9-108">エラーに関する追加情報の一覧。</span><span class="sxs-lookup"><span data-stu-id="07cb9-108">A list of additional details about the error.</span></span></param>
        <summary>
            <span data-ttu-id="07cb9-109">DeleteCertificateError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="07cb9-109">Initializes a new instance of the DeleteCertificateError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.Code" />
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
            <span data-ttu-id="07cb9-110">取得または設定エラーの識別子。</span><span class="sxs-lookup"><span data-stu-id="07cb9-110">Gets or sets an identifier for the error.</span></span> <span data-ttu-id="07cb9-111">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="07cb9-111">Codes are invariant and are intended to be consumed programmatically.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DeleteCertificateError&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.DeleteCertificateError&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of DeleteCertificateError)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DeleteCertificateError&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.Details" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DeleteCertificateError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07cb9-112">取得またはエラーに関する追加情報の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="07cb9-112">Gets or sets a list of additional details about the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.Message" />
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
            <span data-ttu-id="07cb9-113">取得または設定するユーザー インターフェイスでの表示に適したもので、エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="07cb9-113">Gets or sets a message describing the error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07cb9-114">取得または特定のエラーのターゲットを設定します。</span><span class="sxs-lookup"><span data-stu-id="07cb9-114">Gets or sets the target of the particular error.</span></span> <span data-ttu-id="07cb9-115">たとえば、エラー プロパティの名前です。</span><span class="sxs-lookup"><span data-stu-id="07cb9-115">For example, the name of the property in error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DeleteCertificateError.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deleteCertificateError.Validate " />
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
            <span data-ttu-id="07cb9-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="07cb9-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07cb9-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07cb9-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>