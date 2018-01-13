<Type Name="TaskFailureInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation">
  <TypeSignature Language="C#" Value="public class TaskFailureInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskFailureInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskFailureInformation" />
  <TypeSignature Language="F#" Value="type TaskFailureInformation = class" />
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
            <span data-ttu-id="6fa39-101">タスクの失敗に関する情報です。</span><span class="sxs-lookup"><span data-stu-id="6fa39-101">Information about a task failure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskFailureInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.#ctor" />
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
            <span data-ttu-id="6fa39-102">TaskFailureInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6fa39-102">Initializes a new instance of the TaskFailureInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskFailureInformation (Microsoft.Azure.Batch.Protocol.Models.ErrorCategory category, string code = null, string message = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.ErrorCategory category, string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.#ctor(Microsoft.Azure.Batch.Protocol.Models.ErrorCategory,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.NameValuePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (category As ErrorCategory, Optional code As String = null, Optional message As String = null, Optional details As IList(Of NameValuePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation : Microsoft.Azure.Batch.Protocol.Models.ErrorCategory * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation (category, code, message, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="category" Type="Microsoft.Azure.Batch.Protocol.Models.ErrorCategory" />
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;" />
      </Parameters>
      <Docs>
        <param name="category"><span data-ttu-id="6fa39-103">タスク エラーのカテゴリ。</span><span class="sxs-lookup"><span data-stu-id="6fa39-103">The category of the task error.</span></span></param>
        <param name="code"><span data-ttu-id="6fa39-104">タスク エラーの識別子。</span><span class="sxs-lookup"><span data-stu-id="6fa39-104">An identifier for the task error.</span></span> <span data-ttu-id="6fa39-105">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="6fa39-105">Codes are invariant and are intended to be consumed programmatically.</span></span></param>
        <param name="message"><span data-ttu-id="6fa39-106">ユーザー インターフェイスでの表示に適したするもので、タスクのエラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="6fa39-106">A message describing the task error, intended to be suitable for display in a user interface.</span></span></param>
        <param name="details"><span data-ttu-id="6fa39-107">エラーに関連する追加の詳細の一覧。</span><span class="sxs-lookup"><span data-stu-id="6fa39-107">A list of additional details related to the error.</span></span></param>
        <summary>
            <span data-ttu-id="6fa39-108">TaskFailureInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6fa39-108">Initializes a new instance of the TaskFailureInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ErrorCategory Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.ErrorCategory Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As ErrorCategory" />
      <MemberSignature Language="F#" Value="member this.Category : Microsoft.Azure.Batch.Protocol.Models.ErrorCategory with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ErrorCategory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fa39-109">取得またはタスク エラーのカテゴリを設定します。</span><span class="sxs-lookup"><span data-stu-id="6fa39-109">Gets or sets the category of the task error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6fa39-110">使用可能な値が含まれます: 'userError'、'serverError'</span><span class="sxs-lookup"><span data-stu-id="6fa39-110">Possible values include: 'userError', 'serverError'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Code" />
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
            <span data-ttu-id="6fa39-111">取得またはタスク エラーの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="6fa39-111">Gets or sets an identifier for the task error.</span></span> <span data-ttu-id="6fa39-112">コードは変化せず、プログラムでの使用を目的としています。</span><span class="sxs-lookup"><span data-stu-id="6fa39-112">Codes are invariant and are intended to be consumed programmatically.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fa39-113">取得またはエラーに関連する追加の詳細の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6fa39-113">Gets or sets a list of additional details related to the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Message" />
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
            <span data-ttu-id="6fa39-114">取得または設定するユーザー インターフェイスでの表示に適したもので、タスクのエラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="6fa39-114">Gets or sets a message describing the task error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskFailureInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6fa39-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6fa39-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6fa39-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6fa39-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>