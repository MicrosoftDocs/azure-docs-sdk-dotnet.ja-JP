<Type Name="SubscriptionDefinitionsGetOperationStatusHeaders" FullName="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders">
  <TypeSignature Language="C#" Value="public class SubscriptionDefinitionsGetOperationStatusHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionDefinitionsGetOperationStatusHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionDefinitionsGetOperationStatusHeaders" />
  <TypeSignature Language="F#" Value="type SubscriptionDefinitionsGetOperationStatusHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="34928-101">GetOperationStatus 操作のヘッダーを定義します。</span><span class="sxs-lookup"><span data-stu-id="34928-101">Defines headers for GetOperationStatus operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDefinitionsGetOperationStatusHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="34928-102">SubscriptionDefinitionsGetOperationStatusHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="34928-102">Initializes a new instance of the SubscriptionDefinitionsGetOperationStatusHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDefinitionsGetOperationStatusHeaders (string location = null, string retryAfter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string retryAfter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional retryAfter As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders" Usage="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders (location, retryAfter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="retryAfter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="34928-103">非同期操作のステータスを確認できる URL。</span><span class="sxs-lookup"><span data-stu-id="34928-103">The URL where the status of the asynchronous operation can be checked.</span></span></param>
        <param name="retryAfter"><span data-ttu-id="34928-104">操作の状態をチェック中に使用する遅延の量。</span><span class="sxs-lookup"><span data-stu-id="34928-104">The amount of delay to use while the status of the operation is checked.</span></span> <span data-ttu-id="34928-105">値は秒単位で表されます。</span><span class="sxs-lookup"><span data-stu-id="34928-105">The value is expressed in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="34928-106">SubscriptionDefinitionsGetOperationStatusHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="34928-106">Initializes a new instance of the SubscriptionDefinitionsGetOperationStatusHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34928-107">取得または非同期操作のステータスを確認できる URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="34928-107">Gets or sets the URL where the status of the asynchronous operation can be checked.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryAfter">
      <MemberSignature Language="C#" Value="public string RetryAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RetryAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.RetryAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryAfter As String" />
      <MemberSignature Language="F#" Value="member this.RetryAfter : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.RetryAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Retry-After")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34928-108">取得または操作の状態をチェック中に使用する遅延の時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="34928-108">Gets or sets the amount of delay to use while the status of the operation is checked.</span></span> <span data-ttu-id="34928-109">値は秒単位で表されます。</span><span class="sxs-lookup"><span data-stu-id="34928-109">The value is expressed in seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>