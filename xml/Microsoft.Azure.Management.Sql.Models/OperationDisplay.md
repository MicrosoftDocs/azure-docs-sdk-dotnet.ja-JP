<Type Name="OperationDisplay" FullName="Microsoft.Azure.Management.Sql.Models.OperationDisplay">
  <TypeSignature Language="C#" Value="public class OperationDisplay" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationDisplay extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.OperationDisplay" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationDisplay" />
  <TypeSignature Language="F#" Value="type OperationDisplay = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="56e13-101">操作に関連付けられているメタデータを表示します。</span><span class="sxs-lookup"><span data-stu-id="56e13-101">Display metadata associated with the operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationDisplay ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.OperationDisplay.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="56e13-102">OperationDisplay クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="56e13-102">Initializes a new instance of the OperationDisplay class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationDisplay (string provider = null, string resource = null, string operation = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, string resource, string operation, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.OperationDisplay.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provider As String = null, Optional resource As String = null, Optional operation As String = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.OperationDisplay : string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.OperationDisplay" Usage="new Microsoft.Azure.Management.Sql.Models.OperationDisplay (provider, resource, operation, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="provider"><span data-ttu-id="56e13-103">リソース プロバイダーの名前のローカライズされた表示形式。</span><span class="sxs-lookup"><span data-stu-id="56e13-103">The localized friendly form of the resource provider name.</span></span></param>
        <param name="resource"><span data-ttu-id="56e13-104">このアクション/操作に関連するリソースの種類のローカライズされたわかりやすい形式です。</span><span class="sxs-lookup"><span data-stu-id="56e13-104">The localized friendly form of the resource type related to this action/operation.</span></span></param>
        <param name="operation"><span data-ttu-id="56e13-105">操作のローカライズされた表示名。</span><span class="sxs-lookup"><span data-stu-id="56e13-105">The localized friendly name for the operation.</span></span></param>
        <param name="description"><span data-ttu-id="56e13-106">操作のローカライズされたわかりやすい説明。</span><span class="sxs-lookup"><span data-stu-id="56e13-106">The localized friendly description for the operation.</span></span></param>
        <summary>
            <span data-ttu-id="56e13-107">OperationDisplay クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="56e13-107">Initializes a new instance of the OperationDisplay class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.OperationDisplay.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="Microsoft.Azure.Management.Sql.Models.OperationDisplay.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="56e13-108">操作のローカライズされたわかりやすい説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="56e13-108">Gets the localized friendly description for the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.OperationDisplay.Operation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string" Usage="Microsoft.Azure.Management.Sql.Models.OperationDisplay.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="56e13-109">操作のローカライズされた表示名を取得します。</span><span class="sxs-lookup"><span data-stu-id="56e13-109">Gets the localized friendly name for the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.OperationDisplay.Provider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string" Usage="Microsoft.Azure.Management.Sql.Models.OperationDisplay.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="56e13-110">リソース プロバイダーの名前のローカライズされた表示形式を取得します。</span><span class="sxs-lookup"><span data-stu-id="56e13-110">Gets the localized friendly form of the resource provider name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.OperationDisplay.Resource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string" Usage="Microsoft.Azure.Management.Sql.Models.OperationDisplay.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="56e13-111">このアクション/操作に関連するリソースの種類のローカライズされた表示形式を取得します。</span><span class="sxs-lookup"><span data-stu-id="56e13-111">Gets the localized friendly form of the resource type related to this action/operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>