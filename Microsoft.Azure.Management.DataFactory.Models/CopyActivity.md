<Type Name="CopyActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.CopyActivity">
  <TypeSignature Language="C#" Value="public class CopyActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CopyActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.CopyActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class CopyActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type CopyActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Copy")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            アクティビティをコピーします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CopyActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.#ctor" />
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
            CopyActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CopyActivity (string name, Microsoft.Azure.Management.DataFactory.Models.CopySource source, Microsoft.Azure.Management.DataFactory.Models.CopySink sink, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, Microsoft.Azure.Management.DataFactory.Models.CopyTranslator translator = null, object enableStaging = null, Microsoft.Azure.Management.DataFactory.Models.StagingSettings stagingSettings = null, object parallelCopies = null, object cloudDataMovementUnits = null, object enableSkipIncompatibleRow = null, Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings redirectIncompatibleRowSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; inputs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; outputs = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactory.Models.CopySource source, class Microsoft.Azure.Management.DataFactory.Models.CopySink sink, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class Microsoft.Azure.Management.DataFactory.Models.CopyTranslator translator, object enableStaging, class Microsoft.Azure.Management.DataFactory.Models.StagingSettings stagingSettings, object parallelCopies, object cloudDataMovementUnits, object enableSkipIncompatibleRow, class Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings redirectIncompatibleRowSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; inputs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; outputs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.#ctor(System.String,Microsoft.Azure.Management.DataFactory.Models.CopySource,Microsoft.Azure.Management.DataFactory.Models.CopySink,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,Microsoft.Azure.Management.DataFactory.Models.CopyTranslator,System.Object,Microsoft.Azure.Management.DataFactory.Models.StagingSettings,System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.DatasetReference},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.DatasetReference})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.CopyActivity : string * Microsoft.Azure.Management.DataFactory.Models.CopySource * Microsoft.Azure.Management.DataFactory.Models.CopySink * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * Microsoft.Azure.Management.DataFactory.Models.CopyTranslator * obj * Microsoft.Azure.Management.DataFactory.Models.StagingSettings * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.CopyActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.CopyActivity (name, source, sink, additionalProperties, description, dependsOn, linkedServiceName, policy, translator, enableStaging, stagingSettings, parallelCopies, cloudDataMovementUnits, enableSkipIncompatibleRow, redirectIncompatibleRowSettings, inputs, outputs)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="source" Type="Microsoft.Azure.Management.DataFactory.Models.CopySource" />
        <Parameter Name="sink" Type="Microsoft.Azure.Management.DataFactory.Models.CopySink" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="translator" Type="Microsoft.Azure.Management.DataFactory.Models.CopyTranslator" />
        <Parameter Name="enableStaging" Type="System.Object" />
        <Parameter Name="stagingSettings" Type="Microsoft.Azure.Management.DataFactory.Models.StagingSettings" />
        <Parameter Name="parallelCopies" Type="System.Object" />
        <Parameter Name="cloudDataMovementUnits" Type="System.Object" />
        <Parameter Name="enableSkipIncompatibleRow" Type="System.Object" />
        <Parameter Name="redirectIncompatibleRowSettings" Type="Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings" />
        <Parameter Name="inputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;" />
        <Parameter Name="outputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;" />
      </Parameters>
      <Docs>
        <param name="name">アクティビティ名。</param>
        <param name="source">アクティビティをコピーします。</param>
        <param name="sink">アクティビティのシンクをコピーします。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="description">アクティビティの説明です。</param>
        <param name="dependsOn">アクティビティは、条件によって異なります。</param>
        <param name="linkedServiceName">リンクされたサービスの参照。</param>
        <param name="policy">アクティビティ ポリシー。</param>
        <param name="translator">アクティビティ トランスレータをコピーします。 指定がない、表形式の変換が使用されます。</param>
        <param name="enableStaging">中間のステージングを使用してデータをコピーするかどうかを指定します。 既定値は false です。 型: ブール値 (または式の resultType ブール値)。</param>
        <param name="stagingSettings">EnableStaging が true の場合は、中間のステージング設定を指定します。</param>
        <param name="parallelCopies">ソースまたはデータ ストアをオーバー ロードを回避するためのシンクで開かれている同時実行セッションの最大数。
            型: 整数 (または式と resultType 整数)、最小値。
            0.</param>
        <param name="cloudDataMovementUnits">このデータ移動の実行に使用できるクラウド データの移動単位の最大数。
            型: 整数 (または式と resultType 整数)、最小値。
            0.</param>
        <param name="enableSkipIncompatibleRow">互換性のない行をスキップするかどうか。 既定値は false です。 型: ブール値 (または式の resultType ブール値)。</param>
        <param name="redirectIncompatibleRowSettings">EnableSkipIncompatibleRow が true の場合は、互換性のない行の設定をリダイレクトします。</param>
        <param name="inputs">アクティビティの入力の一覧。</param>
        <param name="outputs">アクティビティの出力の一覧です。</param>
        <summary>
            CopyActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudDataMovementUnits">
      <MemberSignature Language="C#" Value="public object CloudDataMovementUnits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object CloudDataMovementUnits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.CloudDataMovementUnits" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudDataMovementUnits As Object" />
      <MemberSignature Language="F#" Value="member this.CloudDataMovementUnits : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.CloudDataMovementUnits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.cloudDataMovementUnits")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのデータ移動の実行に使用できるクラウド データの移動単位の最大数を設定します。 型: 整数 (または式と resultType 整数)、最小値: 0。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSkipIncompatibleRow">
      <MemberSignature Language="C#" Value="public object EnableSkipIncompatibleRow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSkipIncompatibleRow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.EnableSkipIncompatibleRow" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSkipIncompatibleRow As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSkipIncompatibleRow : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.EnableSkipIncompatibleRow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.enableSkipIncompatibleRow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または互換性のない行をスキップするかどうかを設定します。 既定値は false です。 型: ブール値 (または式の resultType ブール値)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableStaging">
      <MemberSignature Language="C#" Value="public object EnableStaging { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableStaging" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.EnableStaging" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableStaging As Object" />
      <MemberSignature Language="F#" Value="member this.EnableStaging : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.EnableStaging" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.enableStaging")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、中間のステージングを使用してデータをコピーするかどうかを指定します。
            既定値は false です。 型: ブール値 (または式の resultType ブール値)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Inputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Inputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Inputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Inputs As IList(Of DatasetReference)" />
      <MemberSignature Language="F#" Value="member this.Inputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Inputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアクティビティの入力の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Outputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Outputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Outputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputs As IList(Of DatasetReference)" />
      <MemberSignature Language="F#" Value="member this.Outputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Outputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアクティビティの出力の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelCopies">
      <MemberSignature Language="C#" Value="public object ParallelCopies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ParallelCopies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.ParallelCopies" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelCopies As Object" />
      <MemberSignature Language="F#" Value="member this.ParallelCopies : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.ParallelCopies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.parallelCopies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはソースまたはデータ ストアをオーバー ロードを回避するためのシンクで開かれている同時実行セッションの最大数を設定します。 型: 整数 (または式と resultType 整数)、最小値: 0。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectIncompatibleRowSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings RedirectIncompatibleRowSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings RedirectIncompatibleRowSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.RedirectIncompatibleRowSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectIncompatibleRowSettings As RedirectIncompatibleRowSettings" />
      <MemberSignature Language="F#" Value="member this.RedirectIncompatibleRowSettings : Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.RedirectIncompatibleRowSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.redirectIncompatibleRowSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または EnableSkipIncompatibleRow が true の場合に、リダイレクトの互換性のない行の設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.CopySink Sink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.CopySink Sink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Sink" />
      <MemberSignature Language="VB.NET" Value="Public Property Sink As CopySink" />
      <MemberSignature Language="F#" Value="member this.Sink : Microsoft.Azure.Management.DataFactory.Models.CopySink with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Sink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CopySink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコピー アクティビティ シンクを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.CopySource Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.CopySource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As CopySource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.DataFactory.Models.CopySource with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CopySource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコピー アクティビティのソースを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StagingSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.StagingSettings StagingSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.StagingSettings StagingSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.StagingSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property StagingSettings As StagingSettings" />
      <MemberSignature Language="F#" Value="member this.StagingSettings : Microsoft.Azure.Management.DataFactory.Models.StagingSettings with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.StagingSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.stagingSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.StagingSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 EnableStaging が true の場合、暫定的なステージングの設定を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Translator">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.CopyTranslator Translator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.CopyTranslator Translator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Translator" />
      <MemberSignature Language="VB.NET" Value="Public Property Translator As CopyTranslator" />
      <MemberSignature Language="F#" Value="member this.Translator : Microsoft.Azure.Management.DataFactory.Models.CopyTranslator with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Translator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.translator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CopyTranslator</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコピー アクティビティ トランスレータを設定します。 指定がない、表形式の変換が使用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CopyActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="copyActivity.Validate " />
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