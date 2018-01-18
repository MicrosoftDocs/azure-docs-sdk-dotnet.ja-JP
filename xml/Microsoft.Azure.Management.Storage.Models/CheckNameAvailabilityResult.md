<Type Name="CheckNameAvailabilityResult" FullName="Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityResult" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="267f6-101">CheckNameAvailability 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="267f6-101">The CheckNameAvailability operation response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="267f6-102">CheckNameAvailabilityResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="267f6-102">Initializes a new instance of the CheckNameAvailabilityResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResult (Nullable&lt;bool&gt; nameAvailable = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt; reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; nameAvailable, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Reason&gt; reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.#ctor(System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.Storage.Models.Reason},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As Nullable(Of Reason) = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult : Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt; * string -&gt; Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult" Usage="new Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult (nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt;" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameAvailable"><span data-ttu-id="267f6-103">名前が使用するために使用できるかどうかを示すブール値を取得します。</span><span class="sxs-lookup"><span data-stu-id="267f6-103">Gets a boolean value that indicates whether the name is available for you to use.</span></span> <span data-ttu-id="267f6-104">True の場合、名前は使用可能なです。</span><span class="sxs-lookup"><span data-stu-id="267f6-104">If true, the name is available.</span></span> <span data-ttu-id="267f6-105">False の場合、名前は既に取得されて有効ではありませんやは使用できません。</span><span class="sxs-lookup"><span data-stu-id="267f6-105">If false, the name has already been taken or is invalid and cannot be used.</span></span></param>
        <param name="reason"><span data-ttu-id="267f6-106">ストレージ アカウント名を使用できませんでした理由を取得します。</span><span class="sxs-lookup"><span data-stu-id="267f6-106">Gets the reason that a storage account name could not be used.</span></span> <span data-ttu-id="267f6-107">Reason 要素は NameAvailable が false の場合にのみ返されます。</span><span class="sxs-lookup"><span data-stu-id="267f6-107">The Reason element is only returned if NameAvailable is false.</span></span> <span data-ttu-id="267f6-108">使用可能な値が含まれます: 'AccountNameInvalid'、'に対する'</span><span class="sxs-lookup"><span data-stu-id="267f6-108">Possible values include: 'AccountNameInvalid', 'AlreadyExists'</span></span></param>
        <param name="message"><span data-ttu-id="267f6-109">さらに詳しく理由の値を示すエラー メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="267f6-109">Gets an error message explaining the Reason value in more detail.</span></span></param>
        <summary>
            <span data-ttu-id="267f6-110">CheckNameAvailabilityResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="267f6-110">Initializes a new instance of the CheckNameAvailabilityResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="267f6-111">さらに詳しく理由の値を示すエラー メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="267f6-111">Gets an error message explaining the Reason value in more detail.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="267f6-112">名前が使用するために使用できるかどうかを示すブール値を取得します。</span><span class="sxs-lookup"><span data-stu-id="267f6-112">Gets a boolean value that indicates whether the name is available for you to use.</span></span> <span data-ttu-id="267f6-113">True の場合、名前は使用可能なです。</span><span class="sxs-lookup"><span data-stu-id="267f6-113">If true, the name is available.</span></span> <span data-ttu-id="267f6-114">False の場合、名前は既に取得されて有効ではありませんやは使用できません。</span><span class="sxs-lookup"><span data-stu-id="267f6-114">If false, the name has already been taken or is invalid and cannot be used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt; Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Reason&gt; Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As Nullable(Of Reason)" />
      <MemberSignature Language="F#" Value="member this.Reason : Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt;" Usage="Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="267f6-115">ストレージ アカウント名を使用できませんでした理由を取得します。</span><span class="sxs-lookup"><span data-stu-id="267f6-115">Gets the reason that a storage account name could not be used.</span></span> <span data-ttu-id="267f6-116">Reason 要素は NameAvailable が false の場合にのみ返されます。</span><span class="sxs-lookup"><span data-stu-id="267f6-116">The Reason element is only returned if NameAvailable is false.</span></span> <span data-ttu-id="267f6-117">使用可能な値が含まれます: 'AccountNameInvalid'、'に対する'</span><span class="sxs-lookup"><span data-stu-id="267f6-117">Possible values include: 'AccountNameInvalid', 'AlreadyExists'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>