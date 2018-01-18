<Type Name="EmailReceiver" FullName="Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver">
  <TypeSignature Language="C#" Value="public class EmailReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EmailReceiver extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Class EmailReceiver" />
  <TypeSignature Language="F#" Value="type EmailReceiver = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d3408-101">電子メールの受信側です。</span><span class="sxs-lookup"><span data-stu-id="d3408-101">An email receiver.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EmailReceiver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d3408-102">EmailReceiver クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3408-102">Initializes a new instance of the EmailReceiver class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EmailReceiver (string name, string emailAddress, Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string emailAddress, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, emailAddress As String, Optional status As Nullable(Of ReceiverStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver : string * string * Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver (name, emailAddress, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="emailAddress" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d3408-103">電子メールの受信者の名前。</span><span class="sxs-lookup"><span data-stu-id="d3408-103">The name of the email receiver.</span></span> <span data-ttu-id="d3408-104">名前は、アクション グループ内の全受信者の間で一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="d3408-104">Names must be unique across all receivers within an action group.</span></span></param>
        <param name="emailAddress"><span data-ttu-id="d3408-105">この受信者の電子メール アドレス。</span><span class="sxs-lookup"><span data-stu-id="d3408-105">The email address of this receiver.</span></span></param>
        <param name="status"><span data-ttu-id="d3408-106">電子メールの受信者の状態。</span><span class="sxs-lookup"><span data-stu-id="d3408-106">The receiver status of the e-mail.</span></span> <span data-ttu-id="d3408-107">使用可能な値が含まれます: 'NotSpecified'、'Enabled'、'無効'</span><span class="sxs-lookup"><span data-stu-id="d3408-107">Possible values include: 'NotSpecified', 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="d3408-108">EmailReceiver クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3408-108">Initializes a new instance of the EmailReceiver class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailAddress">
      <MemberSignature Language="C#" Value="public string EmailAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmailAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.EmailAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailAddress As String" />
      <MemberSignature Language="F#" Value="member this.EmailAddress : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.EmailAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="emailAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3408-109">取得またはこの受信者の電子メール アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="d3408-109">Gets or sets the email address of this receiver.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3408-110">取得または電子メールの受信者の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3408-110">Gets or sets the name of the email receiver.</span></span> <span data-ttu-id="d3408-111">名前は、アクション グループ内の全受信者の間で一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="d3408-111">Names must be unique across all receivers within an action group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of ReceiverStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3408-112">電子メールの受信者の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3408-112">Gets the receiver status of the e-mail.</span></span> <span data-ttu-id="d3408-113">使用可能な値が含まれます: 'NotSpecified'、'Enabled'、'無効'</span><span class="sxs-lookup"><span data-stu-id="d3408-113">Possible values include: 'NotSpecified', 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="emailReceiver.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d3408-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="d3408-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d3408-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3408-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>