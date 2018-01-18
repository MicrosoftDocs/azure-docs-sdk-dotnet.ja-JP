<Type Name="Trigger" FullName="Microsoft.Azure.Management.DataFactory.Models.Trigger">
  <TypeSignature Language="C#" Value="public class Trigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Trigger extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.Trigger" />
  <TypeSignature Language="VB.NET" Value="Public Class Trigger" />
  <TypeSignature Language="F#" Value="type Trigger = class" />
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
            <span data-ttu-id="a5408-101">Azure データ ファクトリ入れ子になったオブジェクトを実行するパイプラインの作成に関する情報を含む</span><span class="sxs-lookup"><span data-stu-id="a5408-101">Azure data factory nested object which contains information about creating pipeline run</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Trigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.Trigger.#ctor" />
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
            <span data-ttu-id="a5408-102">トリガー クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5408-102">Initializes a new instance of the Trigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Trigger (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, string runtimeState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, string runtimeState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.Trigger.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional runtimeState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.Trigger : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.Trigger" Usage="new Microsoft.Azure.Management.DataFactory.Models.Trigger (additionalProperties, description, runtimeState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="runtimeState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="a5408-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="a5408-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="a5408-104">トリガーの説明です。</span><span class="sxs-lookup"><span data-stu-id="a5408-104">Trigger description.</span></span></param>
        <param name="runtimeState"><span data-ttu-id="a5408-105">トリガーが実行されているかを示します。</span><span class="sxs-lookup"><span data-stu-id="a5408-105">Indicates if trigger is running or not.</span></span>
            <span data-ttu-id="a5408-106">トリガーで開始/停止 Api が呼び出されたときに更新されます。</span><span class="sxs-lookup"><span data-stu-id="a5408-106">Updated when Start/Stop APIs are called on the Trigger.</span></span> <span data-ttu-id="a5408-107">使用可能な値が含まれます: 'の開始'、'停止'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="a5408-107">Possible values include: 'Started', 'Stopped', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="a5408-108">トリガー クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5408-108">Initializes a new instance of the Trigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.Trigger.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.Trigger.AdditionalProperties" />
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
            <span data-ttu-id="a5408-109">メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化</span><span class="sxs-lookup"><span data-stu-id="a5408-109">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.Trigger.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.Trigger.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="a5408-110">取得またはトリガーの説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5408-110">Gets or sets trigger description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeState">
      <MemberSignature Language="C#" Value="public string RuntimeState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuntimeState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.Trigger.RuntimeState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuntimeState As String" />
      <MemberSignature Language="F#" Value="member this.RuntimeState : string" Usage="Microsoft.Azure.Management.DataFactory.Models.Trigger.RuntimeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runtimeState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5408-111">取得では、トリガーが実行されているかを示します。</span><span class="sxs-lookup"><span data-stu-id="a5408-111">Gets indicates if trigger is running or not.</span></span> <span data-ttu-id="a5408-112">トリガーで開始/停止 Api が呼び出されたときに更新されます。</span><span class="sxs-lookup"><span data-stu-id="a5408-112">Updated when Start/Stop APIs are called on the Trigger.</span></span> <span data-ttu-id="a5408-113">使用可能な値が含まれます: 'の開始'、'停止'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="a5408-113">Possible values include: 'Started', 'Stopped', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>