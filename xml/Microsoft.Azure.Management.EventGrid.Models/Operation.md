<Type Name="Operation" FullName="Microsoft.Azure.Management.EventGrid.Models.Operation">
  <TypeSignature Language="C#" Value="public class Operation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Operation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.Operation" />
  <TypeSignature Language="VB.NET" Value="Public Class Operation" />
  <TypeSignature Language="F#" Value="type Operation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6a4a9-101">GetOperations 要求によって返される操作を表します</span><span class="sxs-lookup"><span data-stu-id="6a4a9-101">Represents an operation returned by the GetOperations request</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.Operation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6a4a9-102">Operation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6a4a9-102">Initializes a new instance of the Operation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation (string name = null, Microsoft.Azure.Management.EventGrid.Models.OperationInfo display = null, string origin = null, object properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.EventGrid.Models.OperationInfo display, string origin, object properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.Operation.#ctor(System.String,Microsoft.Azure.Management.EventGrid.Models.OperationInfo,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As OperationInfo = null, Optional origin As String = null, Optional properties As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.Operation : string * Microsoft.Azure.Management.EventGrid.Models.OperationInfo * string * obj -&gt; Microsoft.Azure.Management.EventGrid.Models.Operation" Usage="new Microsoft.Azure.Management.EventGrid.Models.Operation (name, display, origin, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.EventGrid.Models.OperationInfo" />
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="properties" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="6a4a9-103">操作の名前</span><span class="sxs-lookup"><span data-stu-id="6a4a9-103">Name of the operation</span></span></param>
        <param name="display"><span data-ttu-id="6a4a9-104">操作の表示名</span><span class="sxs-lookup"><span data-stu-id="6a4a9-104">Display name of the operation</span></span></param>
        <param name="origin"><span data-ttu-id="6a4a9-105">操作の原点です。</span><span class="sxs-lookup"><span data-stu-id="6a4a9-105">Origin of the operation.</span></span> <span data-ttu-id="6a4a9-106">使用可能な値が含まれます: 'User'、'System'、'UserAndSystem'</span><span class="sxs-lookup"><span data-stu-id="6a4a9-106">Possible values include: 'User', 'System', 'UserAndSystem'</span></span></param>
        <param name="properties"><span data-ttu-id="6a4a9-107">操作のプロパティ</span><span class="sxs-lookup"><span data-stu-id="6a4a9-107">Properties of the operation</span></span></param>
        <summary>
            <span data-ttu-id="6a4a9-108">Operation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6a4a9-108">Initializes a new instance of the Operation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.EventGrid.Models.OperationInfo Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.EventGrid.Models.OperationInfo Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.Operation.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As OperationInfo" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.EventGrid.Models.OperationInfo with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.Operation.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.OperationInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a4a9-109">取得または設定操作の表示名</span><span class="sxs-lookup"><span data-stu-id="6a4a9-109">Gets or sets display name of the operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.Operation.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.Operation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
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
            <span data-ttu-id="6a4a9-110">取得または設定操作の名前</span><span class="sxs-lookup"><span data-stu-id="6a4a9-110">Gets or sets name of the operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.Operation.Origin" />
      <MemberSignature Language="VB.NET" Value="Public Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.Operation.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a4a9-111">取得または操作の原点を設定します。</span><span class="sxs-lookup"><span data-stu-id="6a4a9-111">Gets or sets origin of the operation.</span></span> <span data-ttu-id="6a4a9-112">使用可能な値が含まれます: 'User'、'System'、'UserAndSystem'</span><span class="sxs-lookup"><span data-stu-id="6a4a9-112">Possible values include: 'User', 'System', 'UserAndSystem'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public object Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.Operation.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As Object" />
      <MemberSignature Language="F#" Value="member this.Properties : obj with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.Operation.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a4a9-113">取得または設定操作のプロパティ</span><span class="sxs-lookup"><span data-stu-id="6a4a9-113">Gets or sets properties of the operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>