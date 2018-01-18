<Type Name="CheckNameAvailabilityResultInner" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityResultInner" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityResultInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d0887-101">名前の確認可用性要求のプロパティの説明です。</span><span class="sxs-lookup"><span data-stu-id="d0887-101">Description of a Check Name availability request properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d0887-102">CheckNameAvailabilityResultInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d0887-102">Initializes a new instance of the CheckNameAvailabilityResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResultInner (Nullable&lt;bool&gt; nameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; nameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner" Usage="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner (nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameAvailable"><span data-ttu-id="d0887-103">名前空間がある場合、値を示す名前空間は可用性の場合は true です。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="d0887-103">Value indicating namespace is availability, true if the namespace is available; otherwise, false.</span></span></param>
        <param name="reason"><span data-ttu-id="d0887-104">名前空間の非可用理由です。</span><span class="sxs-lookup"><span data-stu-id="d0887-104">The reason for unavailability of a namespace.</span></span>
            <span data-ttu-id="d0887-105">使用可能な値が含まれます 'None'、'InvalidName'、'SubscriptionIsDisabled'、'NameInUse'、'NameInLockdown'、'TooManyNamespaceInCurrentSubscription'。</span><span class="sxs-lookup"><span data-stu-id="d0887-105">Possible values include: 'None', 'InvalidName', 'SubscriptionIsDisabled', 'NameInUse', 'NameInLockdown', 'TooManyNamespaceInCurrentSubscription'</span></span></param>
        <param name="message"><span data-ttu-id="d0887-106">名前空間に関連付けられている理由に関する詳細な情報です。</span><span class="sxs-lookup"><span data-stu-id="d0887-106">The detailed info regarding the reason associated with the namespace.</span></span></param>
        <summary>
            <span data-ttu-id="d0887-107">CheckNameAvailabilityResultInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d0887-107">Initializes a new instance of the CheckNameAvailabilityResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="d0887-108">名前空間に関連付けられている理由をに関する詳細な情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d0887-108">Gets the detailed info regarding the reason associated with the namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="d0887-109">取得または名前空間がある場合、名前空間は可用性の場合、true を示す値を設定それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="d0887-109">Gets or sets value indicating namespace is availability, true if the namespace is available; otherwise, false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0887-110">取得または名前空間が使用できない理由を設定します。</span><span class="sxs-lookup"><span data-stu-id="d0887-110">Gets or sets the reason for unavailability of a namespace.</span></span> <span data-ttu-id="d0887-111">使用可能な値が含まれます 'None'、'InvalidName'、'SubscriptionIsDisabled'、'NameInUse'、'NameInLockdown'、'TooManyNamespaceInCurrentSubscription'。</span><span class="sxs-lookup"><span data-stu-id="d0887-111">Possible values include: 'None', 'InvalidName', 'SubscriptionIsDisabled', 'NameInUse', 'NameInLockdown', 'TooManyNamespaceInCurrentSubscription'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>