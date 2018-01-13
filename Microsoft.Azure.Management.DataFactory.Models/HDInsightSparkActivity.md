<Type Name="HDInsightSparkActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity">
  <TypeSignature Language="C#" Value="public class HDInsightSparkActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightSparkActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightSparkActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type HDInsightSparkActivity = class&#xA;    inherit ExecutionActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("HDInsightSpark")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            HDInsight Spark アクティビティ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightSparkActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.#ctor" />
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
            HDInsightSparkActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightSparkActivity (string name, object rootPath, object entryFilePath, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, System.Collections.Generic.IList&lt;object&gt; arguments = null, string getDebugInfo = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference sparkJobLinkedService = null, string className = null, object proxyUser = null, System.Collections.Generic.IDictionary&lt;string,object&gt; sparkConfig = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object rootPath, object entryFilePath, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class System.Collections.Generic.IList`1&lt;object&gt; arguments, string getDebugInfo, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference sparkJobLinkedService, string className, object proxyUser, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; sparkConfig) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.#ctor(System.String,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Collections.Generic.IList{System.Object},System.String,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.String,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, rootPath As Object, entryFilePath As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional arguments As IList(Of Object) = null, Optional getDebugInfo As String = null, Optional sparkJobLinkedService As LinkedServiceReference = null, Optional className As String = null, Optional proxyUser As Object = null, Optional sparkConfig As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity : string * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * System.Collections.Generic.IList&lt;obj&gt; * string * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * string * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity (name, rootPath, entryFilePath, additionalProperties, description, dependsOn, linkedServiceName, policy, arguments, getDebugInfo, sparkJobLinkedService, className, proxyUser, sparkConfig)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="rootPath" Type="System.Object" />
        <Parameter Name="entryFilePath" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="arguments" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
        <Parameter Name="getDebugInfo" Type="System.String" />
        <Parameter Name="sparkJobLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="className" Type="System.String" />
        <Parameter Name="proxyUser" Type="System.Object" />
        <Parameter Name="sparkConfig" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="name">アクティビティ名。</param>
        <param name="rootPath">ジョブのすべてのファイルの 'sparkJobLinkedService' 内のルート パス。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="entryFilePath">実行されるコード/パッケージのルート フォルダーへの相対パスです。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="description">アクティビティの説明です。</param>
        <param name="dependsOn">アクティビティは、条件によって異なります。</param>
        <param name="linkedServiceName">リンクされたサービスの参照。</param>
        <param name="policy">アクティビティ ポリシー。</param>
        <param name="arguments">HDInsightSparkActivity にユーザー指定の引数。</param>
        <param name="getDebugInfo">デバッグ情報のオプションです。 使用可能な値が含まれます 'None'、'Always' に 'Failure'。</param>
        <param name="sparkJobLinkedService">ストレージのリンクされたサービス エントリ ファイルおよび依存関係、アップロードしてログを受信します。</param>
        <param name="className">アプリケーションの Java/Spark のメイン クラスです。</param>
        <param name="proxyUser">ジョブを実行する権限を借用するユーザー。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="sparkConfig">Spark 構成プロパティです。</param>
        <summary>
            HDInsightSparkActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; Arguments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; Arguments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public Property Arguments As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.Arguments : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.Arguments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.arguments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または HDInsightSparkActivity にユーザーが指定した引数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClassName">
      <MemberSignature Language="C#" Value="public string ClassName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClassName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.ClassName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClassName As String" />
      <MemberSignature Language="F#" Value="member this.ClassName : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.ClassName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.className")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、アプリケーションの Java/Spark のメイン クラスです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntryFilePath">
      <MemberSignature Language="C#" Value="public object EntryFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EntryFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.EntryFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntryFilePath As Object" />
      <MemberSignature Language="F#" Value="member this.EntryFilePath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.EntryFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.entryFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはを実行するコード/パッケージのルート フォルダーへの相対パスを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDebugInfo">
      <MemberSignature Language="C#" Value="public string GetDebugInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GetDebugInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.GetDebugInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property GetDebugInfo As String" />
      <MemberSignature Language="F#" Value="member this.GetDebugInfo : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.GetDebugInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.getDebugInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバッグ情報のオプションを設定します。 使用可能な値が含まれます 'None'、'Always' に 'Failure'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyUser">
      <MemberSignature Language="C#" Value="public object ProxyUser { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ProxyUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.ProxyUser" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyUser As Object" />
      <MemberSignature Language="F#" Value="member this.ProxyUser : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.ProxyUser" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.proxyUser")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブを実行する権限を借用するユーザーを設定します。
            型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RootPath">
      <MemberSignature Language="C#" Value="public object RootPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RootPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.RootPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RootPath As Object" />
      <MemberSignature Language="F#" Value="member this.RootPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.RootPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.rootPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブのすべてのファイルの 'sparkJobLinkedService' のルート パスを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SparkConfig">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; SparkConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; SparkConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.SparkConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property SparkConfig As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.SparkConfig : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.SparkConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sparkConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または spark 構成プロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SparkJobLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference SparkJobLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference SparkJobLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.SparkJobLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property SparkJobLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.SparkJobLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.SparkJobLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sparkJobLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエントリのファイル サービスおよび依存関係をアップロードして、ログを受信するためのストレージのリンクされたサービスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightSparkActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hDInsightSparkActivity.Validate " />
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
  </Members>
</Type>