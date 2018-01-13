<Type Name="HDInsightMapReduceActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity">
  <TypeSignature Language="C#" Value="public class HDInsightMapReduceActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightMapReduceActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightMapReduceActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type HDInsightMapReduceActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("HDInsightMapReduce")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            HDInsight MapReduce アクティビティの型。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightMapReduceActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.#ctor" />
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
            HDInsightMapReduceActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightMapReduceActivity (string name, object className, object jarFilePath, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; storageLinkedServices = null, System.Collections.Generic.IList&lt;object&gt; arguments = null, string getDebugInfo = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference jarLinkedService = null, System.Collections.Generic.IList&lt;object&gt; jarLibs = null, System.Collections.Generic.IDictionary&lt;string,object&gt; defines = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object className, object jarFilePath, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; storageLinkedServices, class System.Collections.Generic.IList`1&lt;object&gt; arguments, string getDebugInfo, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference jarLinkedService, class System.Collections.Generic.IList`1&lt;object&gt; jarLibs, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; defines) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.#ctor(System.String,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference},System.Collections.Generic.IList{System.Object},System.String,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IList{System.Object},System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, className As Object, jarFilePath As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional storageLinkedServices As IList(Of LinkedServiceReference) = null, Optional arguments As IList(Of Object) = null, Optional getDebugInfo As String = null, Optional jarLinkedService As LinkedServiceReference = null, Optional jarLibs As IList(Of Object) = null, Optional defines As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity : string * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; * System.Collections.Generic.IList&lt;obj&gt; * string * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IList&lt;obj&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity (name, className, jarFilePath, additionalProperties, description, dependsOn, linkedServiceName, policy, storageLinkedServices, arguments, getDebugInfo, jarLinkedService, jarLibs, defines)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="className" Type="System.Object" />
        <Parameter Name="jarFilePath" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="storageLinkedServices" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;" />
        <Parameter Name="arguments" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
        <Parameter Name="getDebugInfo" Type="System.String" />
        <Parameter Name="jarLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="jarLibs" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
        <Parameter Name="defines" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="name">アクティビティ名。</param>
        <param name="className">クラスの名前です。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="jarFilePath">Jar のパスです。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="description">アクティビティの説明です。</param>
        <param name="dependsOn">アクティビティは、条件によって異なります。</param>
        <param name="linkedServiceName">リンクされたサービスの参照。</param>
        <param name="policy">アクティビティ ポリシー。</param>
        <param name="storageLinkedServices">ストレージのリンクされたサービスの参照。</param>
        <param name="arguments">ユーザーは、HDInsightActivity への引数を指定します。</param>
        <param name="getDebugInfo">デバッグ情報のオプションです。 使用可能な値が含まれます 'None'、'Always' に 'Failure'。</param>
        <param name="jarLinkedService">リンクされたサービスの参照を jar します。</param>
        <param name="jarLibs">ライブラリを jar します。</param>
        <param name="defines">により、MapReduce ジョブの要求のユーザーを指定するを定義します。</param>
        <summary>
            HDInsightMapReduceActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; Arguments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; Arguments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public Property Arguments As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.Arguments : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.Arguments" />
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
            指定されたユーザーの設定を取得または HDInsightActivity への引数。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClassName">
      <MemberSignature Language="C#" Value="public object ClassName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClassName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.ClassName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClassName As Object" />
      <MemberSignature Language="F#" Value="member this.ClassName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.ClassName" />
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
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラス名を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defines">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Defines { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Defines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.Defines" />
      <MemberSignature Language="VB.NET" Value="Public Property Defines As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Defines : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.Defines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.defines")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            により、取得または設定を指定するユーザーは MapReduce ジョブの要求を定義します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDebugInfo">
      <MemberSignature Language="C#" Value="public string GetDebugInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GetDebugInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.GetDebugInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property GetDebugInfo As String" />
      <MemberSignature Language="F#" Value="member this.GetDebugInfo : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.GetDebugInfo" />
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
    <Member MemberName="JarFilePath">
      <MemberSignature Language="C#" Value="public object JarFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object JarFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property JarFilePath As Object" />
      <MemberSignature Language="F#" Value="member this.JarFilePath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.jarFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または jar のパスを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JarLibs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; JarLibs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; JarLibs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarLibs" />
      <MemberSignature Language="VB.NET" Value="Public Property JarLibs As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.JarLibs : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarLibs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.jarLibs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または jar の lib を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JarLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference JarLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference JarLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property JarLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.JarLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.jarLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、リンクされたサービスの参照を jar します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageLinkedServices">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; StorageLinkedServices { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; StorageLinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.StorageLinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageLinkedServices As IList(Of LinkedServiceReference)" />
      <MemberSignature Language="F#" Value="member this.StorageLinkedServices : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.StorageLinkedServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.storageLinkedServices")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはストレージのリンクされたサービスの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hDInsightMapReduceActivity.Validate " />
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