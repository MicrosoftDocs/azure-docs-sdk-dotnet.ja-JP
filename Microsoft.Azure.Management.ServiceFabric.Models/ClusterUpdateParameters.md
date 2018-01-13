<Type Name="ClusterUpdateParameters" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters">
  <TypeSignature Language="C#" Value="public class ClusterUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterUpdateParameters" />
  <TypeSignature Language="F#" Value="type ClusterUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
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
            クラスター更新の要求
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ClusterUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterUpdateParameters (string reliabilityLevel = null, string upgradeMode = null, string clusterCodeVersion = null, Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription certificate = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; clientCertificateThumbprints = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; clientCertificateCommonNames = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; fabricSettings = null, Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription reverseProxyCertificate = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; nodeTypes = null, Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy upgradeDescription = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string reliabilityLevel, string upgradeMode, string clusterCodeVersion, class Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription certificate, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; clientCertificateThumbprints, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; clientCertificateCommonNames, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; fabricSettings, class Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription reverseProxyCertificate, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; nodeTypes, class Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy upgradeDescription, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription,System.Collections.Generic.IList{Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint},System.Collections.Generic.IList{Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName},System.Collections.Generic.IList{Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription},Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription,System.Collections.Generic.IList{Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription},Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional reliabilityLevel As String = null, Optional upgradeMode As String = null, Optional clusterCodeVersion As String = null, Optional certificate As CertificateDescription = null, Optional clientCertificateThumbprints As IList(Of ClientCertificateThumbprint) = null, Optional clientCertificateCommonNames As IList(Of ClientCertificateCommonName) = null, Optional fabricSettings As IList(Of SettingsSectionDescription) = null, Optional reverseProxyCertificate As CertificateDescription = null, Optional nodeTypes As IList(Of NodeTypeDescription) = null, Optional upgradeDescription As ClusterUpgradePolicy = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters : string * string * string * Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; * Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; * Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters (reliabilityLevel, upgradeMode, clusterCodeVersion, certificate, clientCertificateThumbprints, clientCertificateCommonNames, fabricSettings, reverseProxyCertificate, nodeTypes, upgradeDescription, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="reliabilityLevel" Type="System.String" />
        <Parameter Name="upgradeMode" Type="System.String" />
        <Parameter Name="clusterCodeVersion" Type="System.String" />
        <Parameter Name="certificate" Type="Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription" />
        <Parameter Name="clientCertificateThumbprints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt;" />
        <Parameter Name="clientCertificateCommonNames" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt;" />
        <Parameter Name="fabricSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt;" />
        <Parameter Name="reverseProxyCertificate" Type="Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription" />
        <Parameter Name="nodeTypes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt;" />
        <Parameter Name="upgradeDescription" Type="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="reliabilityLevel">このレベルを使用すると、システム サービスのレプリカの数を設定します。 使用可能な値が含まれます: 'ブロンズ'、'銀色'、'Gold'</param>
        <param name="upgradeMode">クラスターのアップグレード モードでは、かどうかの fabric アップグレードが自動的に開始、システムによってかを示します。 使用可能な値が含まれます '自動'、'Manual'。</param>
        <param name="clusterCodeVersion">場合、ServiceFabric コードのバージョン、設定、upgradeMode を設定するかどうかを確認してください手動にそれ以外の場合と、失敗、PUT を使用している新しいクラスターでは、バージョンを取得することができます ClusterVersions_List を使用すると、既存のクラスターを更新する場合はから取得できます、availableClusterVersions Clusters_Get。</param>
        <param name="certificate">このプライマリ証明書がクラスターにノードのセキュリティ、クラスター管理エンドポイントの SSL 証明書として使用して、既定の管理クライアントを追加する前に、仮想マシン スケール セットまたは Azure key vault で証明書が存在する必要があります。 元の値が上書きされます。</param>
        <param name="clientCertificateThumbprints">クライアント拇印詳細については、クラスター操作用のクライアント アクセスに使用される、既存のコレクションが上書きされます</param>
        <param name="clientCertificateCommonNames">クライアント証明書の共通名に基づくホワイト リストの一覧です。</param>
        <param name="fabricSettings">カスタムの一覧をクラスターを構成するファブリックの設定に注意してください、既存のコレクションが上書きされます</param>
        <param name="reverseProxyCertificate">リバース プロキシの証明書</param>
        <param name="nodeTypes">クラスターを構成する nodetypes の一覧で、それよりも優先されます。</param>
        <param name="upgradeDescription">クラスターをアップグレードするときに使用するポリシー。</param>
        <param name="tags">クラスター更新プログラムのパラメーター</param>
        <summary>
            ClusterUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription Certificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription Certificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificate As CertificateDescription" />
      <MemberSignature Language="F#" Value="member this.Certificate : Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.Certificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クラスターにノードのセキュリティ、クラスター管理エンドポイントと既定管理クライアントの SSL 証明書として使用されるこのプライマリ証明書を取得または設定は、追加する前に、仮想マシン スケール セットまたは Azure key vault で証明書が存在する必要があります。
            元の値が上書きされます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertificateCommonNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; ClientCertificateCommonNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; ClientCertificateCommonNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.ClientCertificateCommonNames" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCertificateCommonNames As IList(Of ClientCertificateCommonName)" />
      <MemberSignature Language="F#" Value="member this.ClientCertificateCommonNames : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.ClientCertificateCommonNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientCertificateCommonNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはホワイト リストの共通名に基づいたクライアントの証明書の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertificateThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; ClientCertificateThumbprints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; ClientCertificateThumbprints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.ClientCertificateThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCertificateThumbprints As IList(Of ClientCertificateThumbprint)" />
      <MemberSignature Language="F#" Value="member this.ClientCertificateThumbprints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.ClientCertificateThumbprints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientCertificateThumbprints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または拇印の詳細については、クライアントを設定クラスター操作用のクライアント アクセスの際に、既存のコレクションが上書きされます
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterCodeVersion">
      <MemberSignature Language="C#" Value="public string ClusterCodeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterCodeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.ClusterCodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterCodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ClusterCodeVersion : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.ClusterCodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clusterCodeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の場合、ServiceFabric コードのバージョン、設定、してください確認してください設定した upgradeMode を手動、それ以外の場合、失敗、PUT を使用している場合、クラスターが新しいバージョンを取得する ClusterVersions_List を使用すると、既存のクラスターを更新する場合はを実行できます。Clusters_Get から、availableClusterVersions を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FabricSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; FabricSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; FabricSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.FabricSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property FabricSettings As IList(Of SettingsSectionDescription)" />
      <MemberSignature Language="F#" Value="member this.FabricSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.FabricSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.fabricSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、クラスターの構成にカスタム ファブリック設定の一覧に注意してください、既存のコレクションが上書きされます
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; NodeTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; NodeTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.NodeTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeTypes As IList(Of NodeTypeDescription)" />
      <MemberSignature Language="F#" Value="member this.NodeTypes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.NodeTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の一覧、クラスターを構成する nodetypes のこれよりも優先されます
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliabilityLevel">
      <MemberSignature Language="C#" Value="public string ReliabilityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReliabilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.ReliabilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ReliabilityLevel As String" />
      <MemberSignature Language="F#" Value="member this.ReliabilityLevel : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.ReliabilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reliabilityLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このレベルを取得または設定をシステム サービスのレプリカの数を設定するために使用するとします。 使用可能な値が含まれます: 'ブロンズ'、'銀色'、'Gold'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReverseProxyCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription ReverseProxyCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription ReverseProxyCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.ReverseProxyCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property ReverseProxyCertificate As CertificateDescription" />
      <MemberSignature Language="F#" Value="member this.ReverseProxyCertificate : Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.ReverseProxyCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reverseProxyCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリバース プロキシの証明書を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
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
            取得または更新プログラムのクラスター パラメーターの設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDescription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy UpgradeDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy UpgradeDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.UpgradeDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDescription As ClusterUpgradePolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradeDescription : Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.UpgradeDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradeDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターをアップグレードするときに使用するポリシーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeMode">
      <MemberSignature Language="C#" Value="public string UpgradeMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.UpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeMode As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeMode : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.UpgradeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradeMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターのアップグレードの設定モードでは、かどうかの fabric アップグレードが自動的に開始、システムによってかを示します。 使用可能な値が含まれます '自動'、'Manual'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clusterUpdateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
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
  </Members>
</Type>