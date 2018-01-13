<Type Name="AzureMLBatchExecutionActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity">
  <TypeSignature Language="C#" Value="public class AzureMLBatchExecutionActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLBatchExecutionActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLBatchExecutionActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type AzureMLBatchExecutionActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureMLBatchExecution")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure ML バッチ実行アクティビティ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLBatchExecutionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity.#ctor" />
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
            AzureMLBatchExecutionActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLBatchExecutionActivity (string name, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, System.Collections.Generic.IDictionary&lt;string,object&gt; globalParameters = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; webServiceOutputs = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; webServiceInputs = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; globalParameters, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; webServiceOutputs, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; webServiceInputs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Collections.Generic.IDictionary{System.String,System.Object},System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile},System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional globalParameters As IDictionary(Of String, Object) = null, Optional webServiceOutputs As IDictionary(Of String, AzureMLWebServiceFile) = null, Optional webServiceInputs As IDictionary(Of String, AzureMLWebServiceFile) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * System.Collections.Generic.IDictionary&lt;string, obj&gt; * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity (name, additionalProperties, description, dependsOn, linkedServiceName, policy, globalParameters, webServiceOutputs, webServiceInputs)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="globalParameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="webServiceOutputs" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt;" />
        <Parameter Name="webServiceInputs" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt;" />
      </Parameters>
      <Docs>
        <param name="name">アクティビティ名。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="description">アクティビティの説明です。</param>
        <param name="dependsOn">アクティビティは、条件によって異なります。</param>
        <param name="linkedServiceName">リンクされたサービスの参照。</param>
        <param name="policy">アクティビティ ポリシー。</param>
        <param name="globalParameters">Azure ML バッチ実行サービス エンドポイントに渡されるキーの値のペア。 キーは、公開済みの Azure ML Web サービスで定義されている、Web サービスのパラメーターの名前と一致する必要があります。 Azure ML バッチ実行要求の globalparameters にあるプロパティに値が渡されます。</param>
        <param name="webServiceOutputs">キー、値のペアの場所の Blob Azure ML エンドポイントの Web サービスの出力の名前を出力を指定する AzureMLWebServiceFile オブジェクトにマッピングします。 この情報は、Azure ML バッチ実行要求の webserviceoutputs にあるプロパティに渡されます。</param>
        <param name="webServiceInputs">キー、値のペア、入力 Blob の場所を指定する AzureMLWebServiceFile オブジェクトへの Azure ML エンドポイントの Web サービスの入力の名前をマッピングする. この情報は、Azure ML バッチ実行要求の WebServiceInputs プロパティに渡されます。</param>
        <summary>
            AzureMLBatchExecutionActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; GlobalParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; GlobalParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity.GlobalParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalParameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.GlobalParameters : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity.GlobalParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.globalParameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキーを Azure ML バッチ実行サービス エンドポイントに渡される値のペアを設定します。 キーは、公開済みの Azure ML Web サービスで定義されている、Web サービスのパラメーターの名前と一致する必要があります。
            Azure ML バッチ実行要求の globalparameters にあるプロパティに値が渡されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureMLBatchExecutionActivity.Validate " />
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
    <Member MemberName="WebServiceInputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; WebServiceInputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; WebServiceInputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity.WebServiceInputs" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceInputs As IDictionary(Of String, AzureMLWebServiceFile)" />
      <MemberSignature Language="F#" Value="member this.WebServiceInputs : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity.WebServiceInputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.webServiceInputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキー、マッピングの入力 Blob の場所を指定する AzureMLWebServiceFile オブジェクトへの Azure ML エンドポイントの Web サービスの入力の名前、値のペアを設定. この情報は、Azure ML バッチ実行要求の WebServiceInputs プロパティに渡されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; WebServiceOutputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; WebServiceOutputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity.WebServiceOutputs" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceOutputs As IDictionary(Of String, AzureMLWebServiceFile)" />
      <MemberSignature Language="F#" Value="member this.WebServiceOutputs : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLBatchExecutionActivity.WebServiceOutputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.webServiceOutputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定キー、値のペア、マッピング AzureMLWebServiceFile オブジェクトの出力を指定するのには、Azure ML エンドポイントの Web サービス出力の名前の Blob の場所。 この情報は、Azure ML バッチ実行要求の webserviceoutputs にあるプロパティに渡されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>