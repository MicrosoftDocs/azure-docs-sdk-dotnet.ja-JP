<Type Name="SubscriptionDefinitionsCreateHeaders" FullName="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders">
  <TypeSignature Language="C#" Value="public class SubscriptionDefinitionsCreateHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionDefinitionsCreateHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionDefinitionsCreateHeaders" />
  <TypeSignature Language="F#" Value="type SubscriptionDefinitionsCreateHeaders = class" />
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
            <span data-ttu-id="3f491-101">作成操作のヘッダーを定義します。</span><span class="sxs-lookup"><span data-stu-id="3f491-101">Defines headers for Create operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDefinitionsCreateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3f491-102">SubscriptionDefinitionsCreateHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f491-102">Initializes a new instance of the SubscriptionDefinitionsCreateHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDefinitionsCreateHeaders (string location = null, string retryAfter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string retryAfter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional retryAfter As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders" Usage="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders (location, retryAfter)" />
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
        <param name="location"><span data-ttu-id="3f491-103">非同期操作の状態を取得するには、この URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="3f491-103">GET this URL to retrieve the status of the asynchronous operation.</span></span></param>
        <param name="retryAfter"><span data-ttu-id="3f491-104">操作の状態をチェック中に使用する遅延の量。</span><span class="sxs-lookup"><span data-stu-id="3f491-104">The amount of delay to use while the status of the operation is checked.</span></span> <span data-ttu-id="3f491-105">値は秒単位で表されます。</span><span class="sxs-lookup"><span data-stu-id="3f491-105">The value is expressed in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="3f491-106">SubscriptionDefinitionsCreateHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f491-106">Initializes a new instance of the SubscriptionDefinitionsCreateHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.Location" />
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
            <span data-ttu-id="3f491-107">取得または設定は、非同期操作の状態を取得するには、この URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="3f491-107">Gets or sets GET this URL to retrieve the status of the asynchronous operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryAfter">
      <MemberSignature Language="C#" Value="public string RetryAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RetryAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.RetryAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryAfter As String" />
      <MemberSignature Language="F#" Value="member this.RetryAfter : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.RetryAfter" />
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
            <span data-ttu-id="3f491-108">取得または操作の状態をチェック中に使用する遅延の時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="3f491-108">Gets or sets the amount of delay to use while the status of the operation is checked.</span></span> <span data-ttu-id="3f491-109">値は秒単位で表されます。</span><span class="sxs-lookup"><span data-stu-id="3f491-109">The value is expressed in seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>