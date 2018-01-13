<Type Name="ConsumerGroup" FullName="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup">
  <TypeSignature Language="C#" Value="public class ConsumerGroup : Microsoft.Azure.Management.EventHub.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConsumerGroup extends Microsoft.Azure.Management.EventHub.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ConsumerGroup&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ConsumerGroup = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventHub.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f4ffa-101">1 つの項目リストまたは取得のコンシューマー グループの操作</span><span class="sxs-lookup"><span data-stu-id="f4ffa-101">Single item in List or Get Consumer group operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConsumerGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f4ffa-102">ConsumerGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4ffa-102">Initializes a new instance of the ConsumerGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConsumerGroup (string id = null, string name = null, string type = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, string userMetadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, string userMetadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.#ctor(System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional createdAt As Nullable(Of DateTime) = null, Optional updatedAt As Nullable(Of DateTime) = null, Optional userMetadata As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventHub.Models.ConsumerGroup : string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.EventHub.Models.ConsumerGroup" Usage="new Microsoft.Azure.Management.EventHub.Models.ConsumerGroup (id, name, type, createdAt, updatedAt, userMetadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="userMetadata" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f4ffa-103">リソース Id</span><span class="sxs-lookup"><span data-stu-id="f4ffa-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="f4ffa-104">リソース名</span><span class="sxs-lookup"><span data-stu-id="f4ffa-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="f4ffa-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="f4ffa-105">Resource type</span></span></param>
        <param name="createdAt"><span data-ttu-id="f4ffa-106">メッセージが作成された正確な時刻です。</span><span class="sxs-lookup"><span data-stu-id="f4ffa-106">Exact time the message was created.</span></span></param>
        <param name="updatedAt"><span data-ttu-id="f4ffa-107">メッセージが更新された正確な時刻です。</span><span class="sxs-lookup"><span data-stu-id="f4ffa-107">The exact time the message was updated.</span></span></param>
        <param name="userMetadata"><span data-ttu-id="f4ffa-108">Usermetadata とは、最大長 1024 を持つユーザー定義の文字列データを格納するプレース ホルダーです。</span><span class="sxs-lookup"><span data-stu-id="f4ffa-108">Usermetadata is a placeholder to store user-defined string data with maximum length 1024.</span></span> <span data-ttu-id="f4ffa-109">例: 説明的なデータを格納するために使用できる、一連のチームとその連絡先情報などもユーザー定義の構成設定を格納できます。</span><span class="sxs-lookup"><span data-stu-id="f4ffa-109">e.g. it can be used to store descriptive data, such as list of teams and their contact information also user-defined configuration settings can be stored.</span></span></param>
        <summary>
            <span data-ttu-id="f4ffa-110">ConsumerGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4ffa-110">Initializes a new instance of the ConsumerGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4ffa-111">メッセージが作成された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4ffa-111">Gets exact time the message was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.updatedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4ffa-112">メッセージが更新された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4ffa-112">Gets the exact time the message was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userMetadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4ffa-113">取得または設定 usermetadata が最大長 1024 を持つユーザー定義の文字列データを格納するプレース ホルダーです。</span><span class="sxs-lookup"><span data-stu-id="f4ffa-113">Gets or sets usermetadata is a placeholder to store user-defined string data with maximum length 1024.</span></span> <span data-ttu-id="f4ffa-114">例: 説明的なデータを格納するために使用できる、一連のチームとその連絡先情報などもユーザー定義の構成設定を格納できます。</span><span class="sxs-lookup"><span data-stu-id="f4ffa-114">e.g. it can be used to store descriptive data, such as list of teams and their contact information also user-defined configuration settings can be stored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>