<Type Name="IntegrationRuntimeStatus" FullName="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus">
  <TypeSignature Language="C#" Value="public class IntegrationRuntimeStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IntegrationRuntimeStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class IntegrationRuntimeStatus" />
  <TypeSignature Language="F#" Value="type IntegrationRuntimeStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c7305-101">ランタイム状態を統合します。</span><span class="sxs-lookup"><span data-stu-id="c7305-101">Integration runtime status.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c7305-102">IntegrationRuntimeStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c7305-102">Initializes a new instance of the IntegrationRuntimeStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeStatus (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string state = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional state As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus" Usage="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus (additionalProperties, state)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="state" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="c7305-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="c7305-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="state"><span data-ttu-id="c7305-104">統合ランタイムの状態。</span><span class="sxs-lookup"><span data-stu-id="c7305-104">The state of integration runtime.</span></span> <span data-ttu-id="c7305-105">使用可能な値が含まれます: '初期'、'停止'、'開始'、'開始'、'停止'、'NeedRegistration'、'オンライン'、'制限'、'オフライン'</span><span class="sxs-lookup"><span data-stu-id="c7305-105">Possible values include: 'Initial', 'Stopped', 'Started', 'Starting', 'Stopping', 'NeedRegistration', 'Online', 'Limited', 'Offline'</span></span></param>
        <summary>
            <span data-ttu-id="c7305-106">IntegrationRuntimeStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c7305-106">Initializes a new instance of the IntegrationRuntimeStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c7305-107">メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化</span><span class="sxs-lookup"><span data-stu-id="c7305-107">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="c7305-108">統合ランタイムの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="c7305-108">Gets the state of integration runtime.</span></span> <span data-ttu-id="c7305-109">使用可能な値が含まれます: '初期'、'停止'、'開始'、'開始'、'停止'、'NeedRegistration'、'オンライン'、'制限'、'オフライン'</span><span class="sxs-lookup"><span data-stu-id="c7305-109">Possible values include: 'Initial', 'Stopped', 'Started', 'Starting', 'Stopping', 'NeedRegistration', 'Online', 'Limited', 'Offline'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>