<Type Name="WorkerPoolResource" FullName="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource">
  <TypeSignature Language="C#" Value="public class WorkerPoolResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WorkerPoolResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
  <TypeSignature Language="VB.NET" Value="Public Class WorkerPoolResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type WorkerPoolResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            App Service 環境の ARM リソースのワーカー プールです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkerPoolResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            WorkerPoolResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkerPoolResource (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;int&gt; workerSizeId = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; computeMode = null, string workerSize = null, Nullable&lt;int&gt; workerCount = null, System.Collections.Generic.IList&lt;string&gt; instanceNames = null, Microsoft.Azure.Management.WebSites.Models.SkuDescription sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;int32&gt; workerSizeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; computeMode, string workerSize, valuetype System.Nullable`1&lt;int32&gt; workerCount, class System.Collections.Generic.IList`1&lt;string&gt; instanceNames, class Microsoft.Azure.Management.WebSites.Models.SkuDescription sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions},System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.WebSites.Models.SkuDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional workerSizeId As Nullable(Of Integer) = null, Optional computeMode As Nullable(Of ComputeModeOptions) = null, Optional workerSize As String = null, Optional workerCount As Nullable(Of Integer) = null, Optional instanceNames As IList(Of String) = null, Optional sku As SkuDescription = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource : string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.WebSites.Models.SkuDescription -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" Usage="new Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource (id, name, kind, type, workerSizeId, computeMode, workerSize, workerCount, instanceNames, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="workerSizeId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="computeMode" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt;" />
        <Parameter Name="workerSize" Type="System.String" />
        <Parameter Name="workerCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="instanceNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.WebSites.Models.SkuDescription" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="workerSizeId">このワーカー プールを参照しているワーカー サイズ ID です。</param>
        <param name="computeMode">共有または専用のアプリケーションをホストします。 使用可能な値が含まれます: 'Shared'、'Dedicated'、'Dynamic'</param>
        <param name="workerSize">ワーカー プールのインスタンスの VM サイズです。</param>
        <param name="workerCount">ワーカー プールのインスタンスの数。</param>
        <param name="instanceNames">ワーカー プール (読み取り専用) のすべてのインスタンスの名前です。</param>
        <param name="sku">To be added.</param>
        <summary>
            WorkerPoolResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; ComputeMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; ComputeMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.ComputeMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputeMode As Nullable(Of ComputeModeOptions)" />
      <MemberSignature Language="F#" Value="member this.ComputeMode : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.ComputeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.computeMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または共有または専用のアプリケーションのホスティングを設定します。 使用可能な値が含まれます: 'Shared'、'Dedicated'、'Dynamic'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; InstanceNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; InstanceNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.InstanceNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.InstanceNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.InstanceNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            (読み取り専用) ワーカー プールのすべてのインスタンスの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SkuDescription Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SkuDescription Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As SkuDescription" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.WebSites.Models.SkuDescription with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SkuDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; WorkerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; WorkerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワーカー プールのインスタンスの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerSize">
      <MemberSignature Language="C#" Value="public string WorkerSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerSize" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerSize As String" />
      <MemberSignature Language="F#" Value="member this.WorkerSize : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワーカー プールのインスタンスの VM サイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerSizeId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; WorkerSizeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; WorkerSizeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerSizeId" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerSizeId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerSizeId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource.WorkerSizeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerSizeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このワーカー プールを参照しているワーカー サイズ ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>