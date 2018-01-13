<Type Name="DataLakeAnalyticsUSQLActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsUSQLActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsUSQLActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsUSQLActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsUSQLActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("DataLakeAnalyticsU-SQL")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            データ Lake Analytics U-SQL アクティビティ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.#ctor" />
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
            DataLakeAnalyticsUSQLActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity (string name, object scriptPath, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference scriptLinkedService, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, object degreeOfParallelism = null, object priority = null, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null, object runtimeVersion = null, object compilationMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object scriptPath, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference scriptLinkedService, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, object degreeOfParallelism, object priority, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters, object runtimeVersion, object compilationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.#ctor(System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, scriptPath As Object, scriptLinkedService As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional degreeOfParallelism As Object = null, Optional priority As Object = null, Optional parameters As IDictionary(Of String, Object) = null, Optional runtimeVersion As Object = null, Optional compilationMode As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity : string * obj * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity (name, scriptPath, scriptLinkedService, additionalProperties, description, dependsOn, linkedServiceName, policy, degreeOfParallelism, priority, parameters, runtimeVersion, compilationMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="scriptPath" Type="System.Object" />
        <Parameter Name="scriptLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="degreeOfParallelism" Type="System.Object" />
        <Parameter Name="priority" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="runtimeVersion" Type="System.Object" />
        <Parameter Name="compilationMode" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name">アクティビティ名。</param>
        <param name="scriptPath">大文字小文字を区別フォルダー パスを U-SQL スクリプトが含まれています。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="scriptLinkedService">スクリプトには、サービス参照の追加がリンクされています。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="description">アクティビティの説明です。</param>
        <param name="dependsOn">アクティビティは、条件によって異なります。</param>
        <param name="linkedServiceName">リンクされたサービスの参照。</param>
        <param name="policy">アクティビティ ポリシー。</param>
        <param name="degreeOfParallelism">ジョブを実行するために同時に使用される最大ノード数。 既定値は 1 です。 型: 整数 (または式と resultType 整数)、最小値。
            1.</param>
        <param name="priority">キューされているすべてのジョブのうち、先に実行するジョブを決定します。 数値が小さいほど、優先度は高くなります。 既定値は 1,000 です。 型: 整数 (または式と resultType 整数)、最小値: 1。</param>
        <param name="parameters">U-SQL ジョブ要求のパラメーターです。</param>
        <param name="runtimeVersion">使用する U SQL エンジンのランタイムのバージョン。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="compilationMode">U-SQL のコンパイル モード。 これらの値のいずれかを指定する必要があります: セマンティック、フル インストール オプションと SingleBox です。 型: 文字列 (または式の resultType 文字列)。</param>
        <summary>
            DataLakeAnalyticsUSQLActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompilationMode">
      <MemberSignature Language="C#" Value="public object CompilationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object CompilationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CompilationMode As Object" />
      <MemberSignature Language="F#" Value="member this.CompilationMode : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.compilationMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または U SQL のコンパイル モードを設定します。 これらの値のいずれかを指定する必要があります: セマンティック、フル インストール オプションと SingleBox です。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DegreeOfParallelism">
      <MemberSignature Language="C#" Value="public object DegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property DegreeOfParallelism As Object" />
      <MemberSignature Language="F#" Value="member this.DegreeOfParallelism : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.degreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの実行に同時に使用されるノードの最大数を設定します。 既定値は 1 です。 型: 整数 (または式と resultType 整数)、最小値: 1。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または U-SQL ジョブ要求のパラメーターを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public object Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Object" />
      <MemberSignature Language="F#" Value="member this.Priority : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、最初に実行するどのジョブからすべてのキューに入っていることを選択する必要がありますを決定します。 数値が小さいほど、優先度は高くなります。 既定値は 1,000 です。 型: 整数 (または式と resultType 整数)、最小値: 1。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeVersion">
      <MemberSignature Language="C#" Value="public object RuntimeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RuntimeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeVersion As Object" />
      <MemberSignature Language="F#" Value="member this.RuntimeVersion : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.runtimeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用する U SQL エンジンのランタイムのバージョンを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ScriptLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ScriptLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.ScriptLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.scriptLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサービス参照のリンクされているスクリプトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptPath">
      <MemberSignature Language="C#" Value="public object ScriptPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ScriptPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptPath As Object" />
      <MemberSignature Language="F#" Value="member this.ScriptPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.scriptPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または U-SQL スクリプトを含むフォルダーに区別するパスを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeAnalyticsUSQLActivity.Validate " />
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