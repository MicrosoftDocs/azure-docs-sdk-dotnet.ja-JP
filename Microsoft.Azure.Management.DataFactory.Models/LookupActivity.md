<Type Name="LookupActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.LookupActivity">
  <TypeSignature Language="C#" Value="public class LookupActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LookupActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.LookupActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class LookupActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type LookupActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Lookup")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            参照アクティビティ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LookupActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.LookupActivity.#ctor" />
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
            LookupActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LookupActivity (string name, Microsoft.Azure.Management.DataFactory.Models.CopySource source, Microsoft.Azure.Management.DataFactory.Models.DatasetReference dataset, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, object firstRowOnly = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactory.Models.CopySource source, class Microsoft.Azure.Management.DataFactory.Models.DatasetReference dataset, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, object firstRowOnly) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.LookupActivity.#ctor(System.String,Microsoft.Azure.Management.DataFactory.Models.CopySource,Microsoft.Azure.Management.DataFactory.Models.DatasetReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, source As CopySource, dataset As DatasetReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional firstRowOnly As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.LookupActivity : string * Microsoft.Azure.Management.DataFactory.Models.CopySource * Microsoft.Azure.Management.DataFactory.Models.DatasetReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.LookupActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.LookupActivity (name, source, dataset, additionalProperties, description, dependsOn, linkedServiceName, policy, firstRowOnly)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="source" Type="Microsoft.Azure.Management.DataFactory.Models.CopySource" />
        <Parameter Name="dataset" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="firstRowOnly" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name">アクティビティ名。</param>
        <param name="source">データセット固有ソースのプロパティ、アクティビティのコピー元と同じです。</param>
        <param name="dataset">参照アクティビティのデータセットの参照。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="description">アクティビティの説明です。</param>
        <param name="dependsOn">アクティビティは、条件によって異なります。</param>
        <param name="linkedServiceName">リンクされたサービスの参照。</param>
        <param name="policy">アクティビティ ポリシー。</param>
        <param name="firstRowOnly">最初の行またはすべての行を返すかどうか。
            既定値は true です。 型: ブール値 (または式の resultType ブール値)。</param>
        <summary>
            LookupActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dataset">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetReference Dataset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetReference Dataset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.LookupActivity.Dataset" />
      <MemberSignature Language="VB.NET" Value="Public Property Dataset As DatasetReference" />
      <MemberSignature Language="F#" Value="member this.Dataset : Microsoft.Azure.Management.DataFactory.Models.DatasetReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.LookupActivity.Dataset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.dataset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DatasetReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または照合アクティビティのデータセットの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirstRowOnly">
      <MemberSignature Language="C#" Value="public object FirstRowOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FirstRowOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.LookupActivity.FirstRowOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property FirstRowOnly As Object" />
      <MemberSignature Language="F#" Value="member this.FirstRowOnly : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.LookupActivity.FirstRowOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.firstRowOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または最初の行またはすべての行を返すかどうかを設定します。 既定値は true です。 型: ブール値 (または式の resultType ブール値)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.CopySource Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.CopySource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.LookupActivity.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As CopySource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.DataFactory.Models.CopySource with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.LookupActivity.Source" />
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
            取得またはアクティビティのコピー元と同じデータセットに固有のソースのプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.LookupActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="lookupActivity.Validate " />
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