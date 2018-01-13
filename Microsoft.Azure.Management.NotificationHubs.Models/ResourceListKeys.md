<Type Name="ResourceListKeys" FullName="Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys">
  <TypeSignature Language="C#" Value="public class ResourceListKeys" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceListKeys extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceListKeys" />
  <TypeSignature Language="F#" Value="type ResourceListKeys = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cb885-101">Namespace と NotificationHub の接続文字列</span><span class="sxs-lookup"><span data-stu-id="cb885-101">Namespace/NotificationHub Connection String</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceListKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cb885-102">ResourceListKeys クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cb885-102">Initializes a new instance of the ResourceListKeys class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceListKeys (string primaryConnectionString = null, string secondaryConnectionString = null, string primaryKey = null, string secondaryKey = null, string keyName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primaryConnectionString, string secondaryConnectionString, string primaryKey, string secondaryKey, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primaryConnectionString As String = null, Optional secondaryConnectionString As String = null, Optional primaryKey As String = null, Optional secondaryKey As String = null, Optional keyName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys : string * string * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys (primaryConnectionString, secondaryConnectionString, primaryKey, secondaryKey, keyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryConnectionString" Type="System.String" />
        <Parameter Name="secondaryConnectionString" Type="System.String" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="primaryConnectionString"><span data-ttu-id="cb885-103">AuthorizationRule PrimaryConnectionString です。</span><span class="sxs-lookup"><span data-stu-id="cb885-103">PrimaryConnectionString of the AuthorizationRule.</span></span></param>
        <param name="secondaryConnectionString"><span data-ttu-id="cb885-104">作成された AuthorizationRule の SecondaryConnectionString</span><span class="sxs-lookup"><span data-stu-id="cb885-104">SecondaryConnectionString of the created AuthorizationRule</span></span></param>
        <param name="primaryKey"><span data-ttu-id="cb885-105">作成された AuthorizationRule の主キー。</span><span class="sxs-lookup"><span data-stu-id="cb885-105">PrimaryKey of the created AuthorizationRule.</span></span></param>
        <param name="secondaryKey"><span data-ttu-id="cb885-106">作成された AuthorizationRule の SecondaryKey</span><span class="sxs-lookup"><span data-stu-id="cb885-106">SecondaryKey of the created AuthorizationRule</span></span></param>
        <param name="keyName"><span data-ttu-id="cb885-107">作成された AuthorizationRule の KeyName</span><span class="sxs-lookup"><span data-stu-id="cb885-107">KeyName of the created AuthorizationRule</span></span></param>
        <summary>
            <span data-ttu-id="cb885-108">ResourceListKeys クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cb885-108">Initializes a new instance of the ResourceListKeys class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb885-109">取得または作成された AuthorizationRule の keyName を設定</span><span class="sxs-lookup"><span data-stu-id="cb885-109">Gets or sets keyName of the created AuthorizationRule</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryConnectionString">
      <MemberSignature Language="C#" Value="public string PrimaryConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.PrimaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryConnectionString : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.PrimaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb885-110">取得または、AuthorizationRule の primaryConnectionString を設定します。</span><span class="sxs-lookup"><span data-stu-id="cb885-110">Gets or sets primaryConnectionString of the AuthorizationRule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb885-111">取得または作成された AuthorizationRule の主キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="cb885-111">Gets or sets primaryKey of the created AuthorizationRule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryConnectionString">
      <MemberSignature Language="C#" Value="public string SecondaryConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.SecondaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryConnectionString : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.SecondaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb885-112">取得または設定の作成の AuthorizationRule secondaryConnectionString</span><span class="sxs-lookup"><span data-stu-id="cb885-112">Gets or sets secondaryConnectionString of the created AuthorizationRule</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb885-113">取得または作成された AuthorizationRule の secondaryKey を設定</span><span class="sxs-lookup"><span data-stu-id="cb885-113">Gets or sets secondaryKey of the created AuthorizationRule</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>