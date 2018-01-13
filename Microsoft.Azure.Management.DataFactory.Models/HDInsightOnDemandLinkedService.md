<Type Name="HDInsightOnDemandLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService">
  <TypeSignature Language="C#" Value="public class HDInsightOnDemandLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightOnDemandLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightOnDemandLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type HDInsightOnDemandLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("HDInsightOnDemand")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            HDInsight オンデマンドのリンクされたサービス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightOnDemandLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.#ctor" />
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
            HDInsightOnDemandLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightOnDemandLinkedService (object clusterSize, object timeToLive, object version, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object hostSubscriptionId, object tenant, object clusterResourceGroup, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object servicePrincipalId = null, Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey = null, object clusterNamePrefix = null, object clusterUserName = null, Microsoft.Azure.Management.DataFactory.Models.SecureString clusterPassword = null, object clusterSshUserName = null, Microsoft.Azure.Management.DataFactory.Models.SecureString clusterSshPassword = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; additionalLinkedServiceNames = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference hcatalogLinkedServiceName = null, object clusterType = null, object sparkVersion = null, object coreConfiguration = null, object hBaseConfiguration = null, object hdfsConfiguration = null, object hiveConfiguration = null, object mapReduceConfiguration = null, object oozieConfiguration = null, object stormConfiguration = null, object yarnConfiguration = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object clusterSize, object timeToLive, object version, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object hostSubscriptionId, object tenant, object clusterResourceGroup, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object servicePrincipalId, class Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey, object clusterNamePrefix, object clusterUserName, class Microsoft.Azure.Management.DataFactory.Models.SecureString clusterPassword, object clusterSshUserName, class Microsoft.Azure.Management.DataFactory.Models.SecureString clusterSshPassword, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; additionalLinkedServiceNames, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference hcatalogLinkedServiceName, object clusterType, object sparkVersion, object coreConfiguration, object hBaseConfiguration, object hdfsConfiguration, object hiveConfiguration, object mapReduceConfiguration, object oozieConfiguration, object stormConfiguration, object yarnConfiguration, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.#ctor(System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clusterSize As Object, timeToLive As Object, version As Object, linkedServiceName As LinkedServiceReference, hostSubscriptionId As Object, tenant As Object, clusterResourceGroup As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional servicePrincipalId As Object = null, Optional servicePrincipalKey As SecureString = null, Optional clusterNamePrefix As Object = null, Optional clusterUserName As Object = null, Optional clusterPassword As SecureString = null, Optional clusterSshUserName As Object = null, Optional clusterSshPassword As SecureString = null, Optional additionalLinkedServiceNames As IList(Of LinkedServiceReference) = null, Optional hcatalogLinkedServiceName As LinkedServiceReference = null, Optional clusterType As Object = null, Optional sparkVersion As Object = null, Optional coreConfiguration As Object = null, Optional hBaseConfiguration As Object = null, Optional hdfsConfiguration As Object = null, Optional hiveConfiguration As Object = null, Optional mapReduceConfiguration As Object = null, Optional oozieConfiguration As Object = null, Optional stormConfiguration As Object = null, Optional yarnConfiguration As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService : obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * obj * obj * obj * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService (clusterSize, timeToLive, version, linkedServiceName, hostSubscriptionId, tenant, clusterResourceGroup, additionalProperties, connectVia, description, servicePrincipalId, servicePrincipalKey, clusterNamePrefix, clusterUserName, clusterPassword, clusterSshUserName, clusterSshPassword, additionalLinkedServiceNames, hcatalogLinkedServiceName, clusterType, sparkVersion, coreConfiguration, hBaseConfiguration, hdfsConfiguration, hiveConfiguration, mapReduceConfiguration, oozieConfiguration, stormConfiguration, yarnConfiguration, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clusterSize" Type="System.Object" />
        <Parameter Name="timeToLive" Type="System.Object" />
        <Parameter Name="version" Type="System.Object" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="hostSubscriptionId" Type="System.Object" />
        <Parameter Name="tenant" Type="System.Object" />
        <Parameter Name="clusterResourceGroup" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="servicePrincipalId" Type="System.Object" />
        <Parameter Name="servicePrincipalKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="clusterNamePrefix" Type="System.Object" />
        <Parameter Name="clusterUserName" Type="System.Object" />
        <Parameter Name="clusterPassword" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="clusterSshUserName" Type="System.Object" />
        <Parameter Name="clusterSshPassword" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="additionalLinkedServiceNames" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;" />
        <Parameter Name="hcatalogLinkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="clusterType" Type="System.Object" />
        <Parameter Name="sparkVersion" Type="System.Object" />
        <Parameter Name="coreConfiguration" Type="System.Object" />
        <Parameter Name="hBaseConfiguration" Type="System.Object" />
        <Parameter Name="hdfsConfiguration" Type="System.Object" />
        <Parameter Name="hiveConfiguration" Type="System.Object" />
        <Parameter Name="mapReduceConfiguration" Type="System.Object" />
        <Parameter Name="oozieConfiguration" Type="System.Object" />
        <Parameter Name="stormConfiguration" Type="System.Object" />
        <Parameter Name="yarnConfiguration" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="clusterSize">クラスター内の worker/データ ノードの数です。 推奨値: 4 です。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="timeToLive">オンデマンド HDInsight クラスターに許可されるアイドル時間です。 他のアクティブなジョブがクラスターにない場合、アクティビティ実行の完了後にオンデマンド HDInsight クラスターが起動状態を維持する時間を指定します。 最小値は、5 分です。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="version">HDInsight クラスターのバージョン。  型: 文字列 (または式の resultType 文字列)。</param>
        <param name="linkedServiceName">データを保存し、処理するためにオンデマンド クラスターで使用される Azure Storage のリンクされたサービスです。</param>
        <param name="hostSubscriptionId">クラスターをホストするお客様のサブスクリプション。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="tenant">テナント id/名前が、サービス プリンシパルが属しています。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="clusterResourceGroup">リソース グループは、クラスターが属しています。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="connectVia">統合のランタイム参照。</param>
        <param name="description">リンクされたサービスの説明。</param>
        <param name="servicePrincipalId">HostSubscriptionId のサービス プリンシパル id。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="servicePrincipalKey">サービス プリンシパルの id キーです。</param>
        <param name="clusterNamePrefix">クラスター名のプレフィックスを後置形式はタイムスタンプを持つ個別になります。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="clusterUserName">クラスターにアクセスするユーザー名。
            型: 文字列 (または式の resultType 文字列)。</param>
        <param name="clusterPassword">クラスターにアクセスするパスワードです。</param>
        <param name="clusterSshUserName">クラスターのノードにリモートで接続する SSH のユーザー名 (Linux の場合)。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="clusterSshPassword">SSH パスワードは、(Linux) のクラスターのノードをリモートで接続します。</param>
        <param name="additionalLinkedServiceNames">Data Factory サービスがあなたの代わりに登録できるように、HDInsight の「リンクされたサービス」の追加ストレージ アカウントを指定します。</param>
        <param name="hcatalogLinkedServiceName">HCatalog データベースを指す Azure SQL のリンクされたサービスの名前。 オンデマンド HDInsight クラスターは、Azure SQL データベースを metastore として使用して作成されます。</param>
        <param name="clusterType">クラスターの種類。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="sparkVersion">Spark クラスターの種類が '発言' の場合のバージョン。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="coreConfiguration">作成する HDInsight クラスターに core 構成パラメーター (core-site.xml と同じ) を指定します。</param>
        <param name="hBaseConfiguration">HDInsight クラスターに HBase 構成パラメーター (hbase-site.xml) を指定します。</param>
        <param name="hdfsConfiguration">HDInsight クラスターに HDFS 構成パラメーター (hdfs-site.xml) を指定します。</param>
        <param name="hiveConfiguration">HDInsight クラスターに hive 構成パラメーター (hive-site.xml) を指定します。</param>
        <param name="mapReduceConfiguration">HDInsight クラスターに MapReduce 構成パラメーター (mapred-site.xml) を指定します。</param>
        <param name="oozieConfiguration">HDInsight クラスターに Oozie 構成パラメーター (oozie-site.xml) を指定します。</param>
        <param name="stormConfiguration">HDInsight クラスターに Storm 構成パラメーター (storm-site.xml) を指定します。</param>
        <param name="yarnConfiguration">HDInsight クラスターに Yarn 構成パラメーター (yarn-site.xml) を指定します。</param>
        <param name="encryptedCredential">暗号化された資格情報の認証に使用します。 資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。 型: 文字列 (または式の resultType 文字列)。</param>
        <summary>
            HDInsightOnDemandLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalLinkedServiceNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; AdditionalLinkedServiceNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; AdditionalLinkedServiceNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.AdditionalLinkedServiceNames" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalLinkedServiceNames As IList(Of LinkedServiceReference)" />
      <MemberSignature Language="F#" Value="member this.AdditionalLinkedServiceNames : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.AdditionalLinkedServiceNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.additionalLinkedServiceNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定できるように、Data Factory サービスで自動的に登録することができます、HDInsight のリンクされたサービスの追加のストレージ アカウントを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterNamePrefix">
      <MemberSignature Language="C#" Value="public object ClusterNamePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterNamePrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterNamePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterNamePrefix As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterNamePrefix : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterNamePrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterNamePrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プレフィックスの設定を取得またはクラスター名の後置にタイムスタンプを持つ個別なります。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ClusterPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ClusterPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.ClusterPassword : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターにアクセスするパスワードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterResourceGroup">
      <MemberSignature Language="C#" Value="public object ClusterResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterResourceGroup As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterResourceGroup : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterResourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターが属している、リソース グループを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSize">
      <MemberSignature Language="C#" Value="public object ClusterSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSize As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterSize : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、クラスター内のワーカー/データ ノードの数を設定します。 推奨値: 4 です。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSshPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ClusterSshPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ClusterSshPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSshPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSshPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.ClusterSshPassword : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSshPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterSshPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または SSH をリモートでパスワードを設定 (Linux) のクラスターのノードを接続します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSshUserName">
      <MemberSignature Language="C#" Value="public object ClusterSshUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterSshUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSshUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSshUserName As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterSshUserName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSshUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterSshUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定する SSH ユーザー名をリモートで接続をクラスターのノードに (for Linux)。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterType">
      <MemberSignature Language="C#" Value="public object ClusterType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterType As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterType : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターの種類を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterUserName">
      <MemberSignature Language="C#" Value="public object ClusterUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterUserName As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterUserName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターにアクセスするユーザー名を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CoreConfiguration">
      <MemberSignature Language="C#" Value="public object CoreConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object CoreConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.CoreConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CoreConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.CoreConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.CoreConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.coreConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を作成する HDInsight クラスターの (core-site.xml) と同じコア構成パラメーターを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または認証に使用される暗号化された資格情報を設定します。
            資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HBaseConfiguration">
      <MemberSignature Language="C#" Value="public object HBaseConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HBaseConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HBaseConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property HBaseConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.HBaseConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HBaseConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hBaseConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、HDInsight クラスターの HBase 構成パラメーター (hbase site.xml) を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HcatalogLinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference HcatalogLinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference HcatalogLinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HcatalogLinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property HcatalogLinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.HcatalogLinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HcatalogLinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hcatalogLinkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リンクされた Azure SQL の名前を取得または設定はサービスを指す HCatalog データベースです。 オンデマンド HDInsight クラスターは、Azure SQL データベースを metastore として使用して作成されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HdfsConfiguration">
      <MemberSignature Language="C#" Value="public object HdfsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HdfsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HdfsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property HdfsConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.HdfsConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HdfsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hdfsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、HDInsight クラスターの HDFS 構成パラメーター (hdfs-site.xml) を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HiveConfiguration">
      <MemberSignature Language="C#" Value="public object HiveConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HiveConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HiveConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property HiveConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.HiveConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HiveConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hiveConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、HDInsight クラスターの hive 構成パラメーター (hive-site.xml) を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostSubscriptionId">
      <MemberSignature Language="C#" Value="public object HostSubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HostSubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HostSubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property HostSubscriptionId As Object" />
      <MemberSignature Language="F#" Value="member this.HostSubscriptionId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HostSubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hostSubscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターをホストする顧客のサブスクリプションを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.linkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または保存して、データの処理のオンデマンドのクラスターで使用される azure Storage のリンクされたサービスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MapReduceConfiguration">
      <MemberSignature Language="C#" Value="public object MapReduceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object MapReduceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.MapReduceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property MapReduceConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.MapReduceConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.MapReduceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.mapReduceConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、HDInsight クラスターの MapReduce 構成パラメーター (mapred-site.xml) を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OozieConfiguration">
      <MemberSignature Language="C#" Value="public object OozieConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object OozieConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.OozieConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property OozieConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.OozieConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.OozieConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.oozieConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、HDInsight クラスターの Oozie 構成パラメーター (oozie-site.xml) を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalId">
      <MemberSignature Language="C#" Value="public object ServicePrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ServicePrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ServicePrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalId As Object" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ServicePrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.servicePrincipalId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、hostSubscriptionId のサービス プリンシパルの id を設定します。
            型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ServicePrincipalKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalKey : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ServicePrincipalKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.servicePrincipalKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサービス プリンシパルの id キーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SparkVersion">
      <MemberSignature Language="C#" Value="public object SparkVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SparkVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.SparkVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property SparkVersion As Object" />
      <MemberSignature Language="F#" Value="member this.SparkVersion : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.SparkVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sparkVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターの種類が 'spark' である場合に、spark のバージョンを設定します。
            型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StormConfiguration">
      <MemberSignature Language="C#" Value="public object StormConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object StormConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.StormConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property StormConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.StormConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.StormConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.stormConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、HDInsight クラスターの Storm 構成パラメーター (storm-site.xml) を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenant">
      <MemberSignature Language="C#" Value="public object Tenant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Tenant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.Tenant" />
      <MemberSignature Language="VB.NET" Value="Public Property Tenant As Object" />
      <MemberSignature Language="F#" Value="member this.Tenant : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.Tenant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.tenant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサービス プリンシパルが所属するテナント id または名前を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public object TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As Object" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.timeToLive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはオンデマンド HDInsight クラスターの最大アイドル時間を設定します。 他のアクティブなジョブがクラスターにない場合、アクティビティ実行の完了後にオンデマンド HDInsight クラスターが起動状態を維持する時間を指定します。 最小値は、5 分です。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hDInsightOnDemandLinkedService.Validate " />
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
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public object Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Object" />
      <MemberSignature Language="F#" Value="member this.Version : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバージョンの HDInsight クラスターを設定します。  型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="YarnConfiguration">
      <MemberSignature Language="C#" Value="public object YarnConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object YarnConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.YarnConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property YarnConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.YarnConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.YarnConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.yarnConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、HDInsight クラスターの Yarn 構成パラメーター (yarn-site.xml) を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>