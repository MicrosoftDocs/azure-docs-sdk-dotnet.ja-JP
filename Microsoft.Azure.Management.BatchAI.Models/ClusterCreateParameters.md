<Type Name="ClusterCreateParameters" FullName="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters">
  <TypeSignature Language="C#" Value="public class ClusterCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterCreateParameters" />
  <TypeSignature Language="F#" Value="type ClusterCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            作成操作に渡されるパラメーター。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ClusterCreateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterCreateParameters (string location, string vmSize, Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings userAccountSettings, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; vmPriority = null, Microsoft.Azure.Management.BatchAI.Models.ScaleSettings scaleSettings = null, Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration virtualMachineConfiguration = null, Microsoft.Azure.Management.BatchAI.Models.NodeSetup nodeSetup = null, Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string vmSize, class Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings userAccountSettings, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; vmPriority, class Microsoft.Azure.Management.BatchAI.Models.ScaleSettings scaleSettings, class Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration virtualMachineConfiguration, class Microsoft.Azure.Management.BatchAI.Models.NodeSetup nodeSetup, class Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.BatchAI.Models.VmPriority},Microsoft.Azure.Management.BatchAI.Models.ScaleSettings,Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration,Microsoft.Azure.Management.BatchAI.Models.NodeSetup,Microsoft.Azure.Management.BatchAI.Models.ResourceId)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters : string * string * Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; * Microsoft.Azure.Management.BatchAI.Models.ScaleSettings * Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration * Microsoft.Azure.Management.BatchAI.Models.NodeSetup * Microsoft.Azure.Management.BatchAI.Models.ResourceId -&gt; Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" Usage="new Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters (location, vmSize, userAccountSettings, tags, vmPriority, scaleSettings, virtualMachineConfiguration, nodeSetup, subnet)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="userAccountSettings" Type="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="vmPriority" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt;" />
        <Parameter Name="scaleSettings" Type="Microsoft.Azure.Management.BatchAI.Models.ScaleSettings" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration" />
        <Parameter Name="nodeSetup" Type="Microsoft.Azure.Management.BatchAI.Models.NodeSetup" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
      </Parameters>
      <Docs>
        <param name="location">クラスターを作成するための領域。</param>
        <param name="vmSize">クラスター内の仮想マシンのサイズ。</param>
        <param name="userAccountSettings">クラスターのすべてのコンピューティング ノードで作成されるユーザー アカウントの設定です。</param>
        <param name="tags">ユーザーは、クラスターに関連付けられているタグを指定します。</param>
        <param name="vmPriority">専用または lowpriority です。</param>
        <param name="scaleSettings">クラスターの必要な小数点以下桁数。</param>
        <param name="virtualMachineConfiguration">OS イメージと、マウントされたデータ ボリュームの設定です。</param>
        <param name="nodeSetup">クラスター内のすべてのコンピューティング ノードで実行するように設定します。</param>
        <param name="subnet">サブネットの識別子を指定します。
            </param>
        <summary>
            ClusterCreateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            取得またはクラスターを作成するための領域を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeSetup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.NodeSetup NodeSetup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.NodeSetup NodeSetup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.NodeSetup" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeSetup As NodeSetup" />
      <MemberSignature Language="F#" Value="member this.NodeSetup : Microsoft.Azure.Management.BatchAI.Models.NodeSetup with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.NodeSetup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeSetup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.NodeSetup</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスター内のすべてのコンピューティング ノードで実行するセットアップを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ScaleSettings ScaleSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ScaleSettings ScaleSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.ScaleSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleSettings As ScaleSettings" />
      <MemberSignature Language="F#" Value="member this.ScaleSettings : Microsoft.Azure.Management.BatchAI.Models.ScaleSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.ScaleSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターの適切な規模を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、サブネットの識別子を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、ユーザーは、クラスターに関連付けられているタグを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccountSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings UserAccountSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings UserAccountSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.UserAccountSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccountSettings As UserAccountSettings" />
      <MemberSignature Language="F#" Value="member this.UserAccountSettings : Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.UserAccountSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userAccountSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターのすべてのコンピューティング ノードで作成されるユーザー アカウントの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clusterCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachineConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または OS イメージと、マウントされたデータ ボリュームの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmPriority">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; VmPriority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; VmPriority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VmPriority" />
      <MemberSignature Language="VB.NET" Value="Public Property VmPriority As Nullable(Of VmPriority)" />
      <MemberSignature Language="F#" Value="member this.VmPriority : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VmPriority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmPriority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定専用または lowpriority します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は専用です。 使用可能な値が含まれます: '専用'、'lowpriority'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスター内の仮想マシンのサイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            クラスター内のすべての仮想マシンは、同じサイズです。 仮想マシンのマーケットプ レースからイメージを使用して、クラスターの使用可能な VM サイズについては ((Linux) の仮想マシンのサイズを参照してください (Windows) の仮想マシンのサイズ。 AI バッチ サービスは、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズをサポートします。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>