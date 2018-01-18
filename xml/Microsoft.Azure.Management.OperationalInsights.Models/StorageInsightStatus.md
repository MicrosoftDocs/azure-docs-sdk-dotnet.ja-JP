<Type Name="StorageInsightStatus" FullName="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus">
  <TypeSignature Language="C#" Value="public class StorageInsightStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageInsightStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageInsightStatus" />
  <TypeSignature Language="F#" Value="type StorageInsightStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5cab6-101">記憶域 insight の状態です。</span><span class="sxs-lookup"><span data-stu-id="5cab6-101">The status of the storage insight.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageInsightStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5cab6-102">StorageInsightStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5cab6-102">Initializes a new instance of the StorageInsightStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageInsightStatus (string state, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string state, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As String, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus : string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus (state, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="state"><span data-ttu-id="5cab6-103">ワークスペースに、ストレージ インサイトの接続の状態。</span><span class="sxs-lookup"><span data-stu-id="5cab6-103">The state of the storage insight connection to the workspace.</span></span> <span data-ttu-id="5cab6-104">使用可能な値が含まれます: 'OK'、'ERROR'</span><span class="sxs-lookup"><span data-stu-id="5cab6-104">Possible values include: 'OK', 'ERROR'</span></span></param>
        <param name="description"><span data-ttu-id="5cab6-105">記憶域 insight の状態の説明です。</span><span class="sxs-lookup"><span data-stu-id="5cab6-105">Description of the state of the storage insight.</span></span></param>
        <summary>
            <span data-ttu-id="5cab6-106">StorageInsightStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5cab6-106">Initializes a new instance of the StorageInsightStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
            <span data-ttu-id="5cab6-107">取得または記憶域 insight の状態の説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="5cab6-107">Gets or sets description of the state of the storage insight.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5cab6-108">取得またはワークスペースに、ストレージ インサイトの接続の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="5cab6-108">Gets or sets the state of the storage insight connection to the workspace.</span></span> <span data-ttu-id="5cab6-109">使用可能な値が含まれます: 'OK'、'ERROR'</span><span class="sxs-lookup"><span data-stu-id="5cab6-109">Possible values include: 'OK', 'ERROR'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageInsightStatus.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5cab6-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5cab6-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5cab6-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5cab6-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>