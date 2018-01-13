<Type Name="IntegrationRuntimeComputeProperties" FullName="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties">
  <TypeSignature Language="C#" Value="public class IntegrationRuntimeComputeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IntegrationRuntimeComputeProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class IntegrationRuntimeComputeProperties" />
  <TypeSignature Language="F#" Value="type IntegrationRuntimeComputeProperties = class" />
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
            管理されている統合ランタイムのコンピューティング リソースのプロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeComputeProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.#ctor" />
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
            IntegrationRuntimeComputeProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeComputeProperties (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string location = null, string nodeSize = null, Nullable&lt;int&gt; numberOfNodes = null, Nullable&lt;int&gt; maxParallelExecutionsPerNode = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeVNetProperties vNetProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string location, string nodeSize, valuetype System.Nullable`1&lt;int32&gt; numberOfNodes, valuetype System.Nullable`1&lt;int32&gt; maxParallelExecutionsPerNode, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeVNetProperties vNetProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeVNetProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional location As String = null, Optional nodeSize As String = null, Optional numberOfNodes As Nullable(Of Integer) = null, Optional maxParallelExecutionsPerNode As Nullable(Of Integer) = null, Optional vNetProperties As IntegrationRuntimeVNetProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeVNetProperties -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties" Usage="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties (additionalProperties, location, nodeSize, numberOfNodes, maxParallelExecutionsPerNode, vNetProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="nodeSize" Type="System.String" />
        <Parameter Name="numberOfNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxParallelExecutionsPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="vNetProperties" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeVNetProperties" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="location">管理されている統合ランタイムの場所です。 サポートされているリージョンは https://docs.microsoft.com/en-us/azure/data-factory/data-factory-data-movement-activities で見つかりませんでした。</param>
        <param name="nodeSize">ノードのサイズ要件には、統合ランタイムを管理します。</param>
        <param name="numberOfNodes">管理されている統合ランタイムのノードの必要な数。</param>
        <param name="maxParallelExecutionsPerNode">最大の並列実行は、管理されている統合ランタイムのノードごとにカウントします。</param>
        <param name="vNetProperties">管理されている統合ランタイムの VNet プロパティです。</param>
        <summary>
            IntegrationRuntimeComputeProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.AdditionalProperties" />
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
            メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはマネージ統合ランタイムの場所を設定します。 サポートされているリージョンは https://docs.microsoft.com/en-us/azure/data-factory/data-factory-data-movement-activities で見つかりませんでした。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxParallelExecutionsPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxParallelExecutionsPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxParallelExecutionsPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.MaxParallelExecutionsPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxParallelExecutionsPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxParallelExecutionsPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.MaxParallelExecutionsPerNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxParallelExecutionsPerNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはマネージ統合ランタイムのノードあたりの並列実行の最大数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeSize">
      <MemberSignature Language="C#" Value="public string NodeSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.NodeSize" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeSize As String" />
      <MemberSignature Language="F#" Value="member this.NodeSize : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.NodeSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはマネージの統合の実行時に、ノードのサイズ要件を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.NumberOfNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.NumberOfNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numberOfNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはマネージ統合ランタイムのノードの必要な数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="integrationRuntimeComputeProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VNetProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeVNetProperties VNetProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeVNetProperties VNetProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.VNetProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property VNetProperties As IntegrationRuntimeVNetProperties" />
      <MemberSignature Language="F#" Value="member this.VNetProperties : Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeVNetProperties with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties.VNetProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vNetProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeVNetProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはマネージ統合ランタイムの vNet のプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>