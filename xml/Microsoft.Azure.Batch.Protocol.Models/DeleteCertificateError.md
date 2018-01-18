<Type Name="DeleteCertificateError" FullName="Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError">
  <TypeSignature Language="C#" Value="public class DeleteCertificateError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeleteCertificateError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError" />
  <TypeSignature Language="VB.NET" Value="Public Class DeleteCertificateError" />
  <TypeSignature Language="F#" Value="type DeleteCertificateError = class" />
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
            <span data-ttu-id="fdb1f-101">証明書を削除するときに、バッチ サービスで発生したエラーです。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-101">An error encountered by the Batch service when deleting a certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeleteCertificateError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.#ctor" />
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
            <span data-ttu-id="fdb1f-102">DeleteCertificateError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-102">Initializes a new instance of the DeleteCertificateError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeleteCertificateError (string code = null, string message = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; values = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.NameValuePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional values As IList(Of NameValuePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError" Usage="new Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError (code, message, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="fdb1f-103">証明書の削除エラーの識別子。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-103">An identifier for the certificate deletion error.</span></span> <span data-ttu-id="fdb1f-104">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-104">Codes are invariant and are intended to be consumed programmatically.</span></span></param>
        <param name="message"><span data-ttu-id="fdb1f-105">ユーザー インターフェイスでの表示に適したするもので、証明書の削除エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-105">A message describing the certificate deletion error, intended to be suitable for display in a user interface.</span></span></param>
        <param name="values"><span data-ttu-id="fdb1f-106">証明書の削除エラーに関連する追加のエラー詳細の一覧。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-106">A list of additional error details related to the certificate deletion error.</span></span></param>
        <summary>
            <span data-ttu-id="fdb1f-107">DeleteCertificateError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-107">Initializes a new instance of the DeleteCertificateError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Code" />
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
            <span data-ttu-id="fdb1f-108">取得または証明書の削除エラーの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-108">Gets or sets an identifier for the certificate deletion error.</span></span>
            <span data-ttu-id="fdb1f-109">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-109">Codes are invariant and are intended to be consumed programmatically.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Message" />
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
            <span data-ttu-id="fdb1f-110">取得または設定するユーザー インターフェイスでの表示に適したもので、証明書の削除エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-110">Gets or sets a message describing the certificate deletion error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb1f-111">取得または証明書の削除エラーに関連する追加のエラー詳細の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-111">Gets or sets a list of additional error details related to the certificate deletion error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fdb1f-112">この一覧には、アクティブなプールこの証明書を参照しているノードなどの詳細が含まれています。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-112">This list includes details such as the active pools and nodes referencing this certificate.</span></span> <span data-ttu-id="fdb1f-113">ただし、大量のリソースは、証明書を参照する場合は、最初の 100 についてのみ説明の一覧が含まれます。</span><span class="sxs-lookup"><span data-stu-id="fdb1f-113">However, if a large number of resources reference the certificate, the list contains only about the first hundred.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>