<Type Name="OperationDisplay" FullName="Microsoft.Azure.Management.BatchAI.Models.OperationDisplay">
  <TypeSignature Language="C#" Value="public class OperationDisplay" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationDisplay extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.OperationDisplay" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationDisplay" />
  <TypeSignature Language="F#" Value="type OperationDisplay = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="99bd5-101">操作を記述するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="99bd5-101">The object that describes the operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationDisplay ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OperationDisplay.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="99bd5-102">OperationDisplay クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="99bd5-102">Initializes a new instance of the OperationDisplay class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationDisplay (string provider = null, string operation = null, string resource = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, string operation, string resource, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OperationDisplay.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provider As String = null, Optional operation As String = null, Optional resource As String = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.OperationDisplay : string * string * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.OperationDisplay" Usage="new Microsoft.Azure.Management.BatchAI.Models.OperationDisplay (provider, operation, resource, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="provider"><span data-ttu-id="99bd5-103">リソース プロバイダーのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="99bd5-103">Friendly name of the resource provider.</span></span></param>
        <param name="operation"><span data-ttu-id="99bd5-104">操作の種類。</span><span class="sxs-lookup"><span data-stu-id="99bd5-104">The operation type.</span></span></param>
        <param name="resource"><span data-ttu-id="99bd5-105">操作が実行されるリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="99bd5-105">The resource type on which the operation is performed.</span></span></param>
        <param name="description"><span data-ttu-id="99bd5-106">操作のフレンドリ名</span><span class="sxs-lookup"><span data-stu-id="99bd5-106">The friendly name of the operation</span></span></param>
        <summary>
            <span data-ttu-id="99bd5-107">OperationDisplay クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="99bd5-107">Initializes a new instance of the OperationDisplay class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OperationDisplay.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OperationDisplay.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99bd5-108">取得または設定操作のフレンドリ名</span><span class="sxs-lookup"><span data-stu-id="99bd5-108">Gets or sets the friendly name of the operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OperationDisplay.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OperationDisplay.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99bd5-109">取得または操作の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="99bd5-109">Gets or sets the operation type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="99bd5-110">例: 読み取り、書き込み、削除、または listKeys/アクション</span><span class="sxs-lookup"><span data-stu-id="99bd5-110">For example: read, write, delete, or listKeys/action</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OperationDisplay.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OperationDisplay.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99bd5-111">取得またはリソース プロバイダーのフレンドリ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="99bd5-111">Gets or sets friendly name of the resource provider.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OperationDisplay.Resource" />
      <MemberSignature Language="VB.NET" Value="Public Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OperationDisplay.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99bd5-112">取得または操作が実行されるリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="99bd5-112">Gets or sets the resource type on which the operation is performed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>