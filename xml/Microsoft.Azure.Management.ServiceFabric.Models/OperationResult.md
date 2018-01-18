<Type Name="OperationResult" FullName="Microsoft.Azure.Management.ServiceFabric.Models.OperationResult">
  <TypeSignature Language="C#" Value="public class OperationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.OperationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationResult" />
  <TypeSignature Language="F#" Value="type OperationResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d48da-101">使用可能な操作の一覧の結果</span><span class="sxs-lookup"><span data-stu-id="d48da-101">Available operation list result</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.OperationResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d48da-102">OperationResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d48da-102">Initializes a new instance of the OperationResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationResult (string name = null, Microsoft.Azure.Management.ServiceFabric.Models.AvailableOperationDisplay display = null, string origin = null, string nextLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.ServiceFabric.Models.AvailableOperationDisplay display, string origin, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.OperationResult.#ctor(System.String,Microsoft.Azure.Management.ServiceFabric.Models.AvailableOperationDisplay,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As AvailableOperationDisplay = null, Optional origin As String = null, Optional nextLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.OperationResult : string * Microsoft.Azure.Management.ServiceFabric.Models.AvailableOperationDisplay * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.OperationResult" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.OperationResult (name, display, origin, nextLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.ServiceFabric.Models.AvailableOperationDisplay" />
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d48da-103">結果の名前</span><span class="sxs-lookup"><span data-stu-id="d48da-103">Result name</span></span></param>
        <param name="display"><span data-ttu-id="d48da-104">結果の dispaly</span><span class="sxs-lookup"><span data-stu-id="d48da-104">Dispaly of the result</span></span></param>
        <param name="origin"><span data-ttu-id="d48da-105">配信元の結果</span><span class="sxs-lookup"><span data-stu-id="d48da-105">Origin result</span></span></param>
        <param name="nextLink"><span data-ttu-id="d48da-106">次の結果セットを取得するために使用する URL。</span><span class="sxs-lookup"><span data-stu-id="d48da-106">The URL to use for getting the next set of results.</span></span></param>
        <summary>
            <span data-ttu-id="d48da-107">OperationResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d48da-107">Initializes a new instance of the OperationResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.AvailableOperationDisplay Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.AvailableOperationDisplay Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.OperationResult.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As AvailableOperationDisplay" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.ServiceFabric.Models.AvailableOperationDisplay with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.OperationResult.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.AvailableOperationDisplay</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d48da-108">取得または設定の結果の表示</span><span class="sxs-lookup"><span data-stu-id="d48da-108">Gets or sets dispaly of the result</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.OperationResult.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.OperationResult.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="d48da-109">取得または設定の結果名</span><span class="sxs-lookup"><span data-stu-id="d48da-109">Gets or sets result name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.OperationResult.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.OperationResult.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d48da-110">取得または次の結果セットを取得するために使用する URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="d48da-110">Gets or sets the URL to use for getting the next set of results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.OperationResult.Origin" />
      <MemberSignature Language="VB.NET" Value="Public Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.OperationResult.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="d48da-111">配信元の結果取得または設定</span><span class="sxs-lookup"><span data-stu-id="d48da-111">Gets or sets origin result</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>