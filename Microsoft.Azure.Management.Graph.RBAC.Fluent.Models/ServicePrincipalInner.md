<Type Name="ServicePrincipalInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner">
  <TypeSignature Language="C#" Value="public class ServicePrincipalInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServicePrincipalInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ServicePrincipalInner" />
  <TypeSignature Language="F#" Value="type ServicePrincipalInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b0977-101">Active Directory サービス プリンシパル情報。</span><span class="sxs-lookup"><span data-stu-id="b0977-101">Active Directory service principal information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePrincipalInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b0977-102">ServicePrincipalInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b0977-102">Initializes a new instance of the ServicePrincipalInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePrincipalInner (string objectId = null, string objectType = null, string displayName = null, string appId = null, System.Collections.Generic.IList&lt;string&gt; servicePrincipalNames = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string objectId, string objectType, string displayName, string appId, class System.Collections.Generic.IList`1&lt;string&gt; servicePrincipalNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional objectId As String = null, Optional objectType As String = null, Optional displayName As String = null, Optional appId As String = null, Optional servicePrincipalNames As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner : string * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner (objectId, objectType, displayName, appId, servicePrincipalNames)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="objectType" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="appId" Type="System.String" />
        <Parameter Name="servicePrincipalNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="objectId"><span data-ttu-id="b0977-103">オブジェクト ID。</span><span class="sxs-lookup"><span data-stu-id="b0977-103">The object ID.</span></span></param>
        <param name="objectType"><span data-ttu-id="b0977-104">オブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="b0977-104">The object type.</span></span></param>
        <param name="displayName"><span data-ttu-id="b0977-105">サービス プリンシパルの表示名。</span><span class="sxs-lookup"><span data-stu-id="b0977-105">The display name of the service principal.</span></span></param>
        <param name="appId"><span data-ttu-id="b0977-106">アプリケーション ID。</span><span class="sxs-lookup"><span data-stu-id="b0977-106">The application ID.</span></span></param>
        <param name="servicePrincipalNames"><span data-ttu-id="b0977-107">サービス プリンシパル名のコレクション。</span><span class="sxs-lookup"><span data-stu-id="b0977-107">A collection of service principal names.</span></span></param>
        <summary>
            <span data-ttu-id="b0977-108">ServicePrincipalInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b0977-108">Initializes a new instance of the ServicePrincipalInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppId">
      <MemberSignature Language="C#" Value="public string AppId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.AppId" />
      <MemberSignature Language="VB.NET" Value="Public Property AppId As String" />
      <MemberSignature Language="F#" Value="member this.AppId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.AppId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="appId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0977-109">取得または設定、アプリケーションの id です。</span><span class="sxs-lookup"><span data-stu-id="b0977-109">Gets or sets the application ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0977-110">取得またはプリンシパル、サービスの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="b0977-110">Gets or sets the display name of the service principal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public string ObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectId As String" />
      <MemberSignature Language="F#" Value="member this.ObjectId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.ObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="objectId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0977-111">取得または設定オブジェクトの id です。</span><span class="sxs-lookup"><span data-stu-id="b0977-111">Gets or sets the object ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectType">
      <MemberSignature Language="C#" Value="public string ObjectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.ObjectType" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectType As String" />
      <MemberSignature Language="F#" Value="member this.ObjectType : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.ObjectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="objectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0977-112">取得またはオブジェクトの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="b0977-112">Gets or sets the object type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ServicePrincipalNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ServicePrincipalNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.ServicePrincipalNames" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ServicePrincipalInner.ServicePrincipalNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="servicePrincipalNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0977-113">取得またはサービス プリンシパル名のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="b0977-113">Gets or sets a collection of service principal names.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>