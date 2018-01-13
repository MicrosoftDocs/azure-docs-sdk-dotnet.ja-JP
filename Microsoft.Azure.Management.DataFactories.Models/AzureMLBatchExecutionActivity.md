<Type Name="AzureMLBatchExecutionActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity">
  <TypeSignature Language="C#" Value="public class AzureMLBatchExecutionActivity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLBatchExecutionActivity extends Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLBatchExecutionActivity&#xA;Inherits ActivityTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureMLBatchExecutionActivity = class&#xA;    inherit ActivityTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureMLBatchExecution")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure ML バッチ実行サービス アクティビティ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLBatchExecutionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; GlobalParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GlobalParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.GlobalParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalParameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GlobalParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.GlobalParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 Azure ML バッチ実行サービス エンドポイントに渡されるキーの値のペア。 キーは、公開済みの Azure ML Web サービスで定義されている、Web サービスのパラメーターの名前と一致する必要があります。 値には、各スライスの実行時 (を参照してください http://go.microsoft.com/fwlink/?LinkId=823697) に解決する Azure Data Factory 関数を含めることがあります。 Azure ML バッチ実行要求の globalparameters にあるプロパティに値が渡されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceInput">
      <MemberSignature Language="C#" Value="public string WebServiceInput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WebServiceInput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInput" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceInput As String" />
      <MemberSignature Language="F#" Value="member this.WebServiceInput : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInput" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 バッチ実行への入力を提供するデータ ファクトリのデータセットの名前です。 この情報は、Azure ML バッチ実行要求の WebServiceInput プロパティに渡されます。 WebServiceInput は、WebServiceInputs で同時には使用できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceInputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; WebServiceInputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; WebServiceInputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInputs" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceInputs As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.WebServiceInputs : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 マッピングに Data Factory のデータセットの名前の Azure ML web サービスの入力の名前、キーの値のペア。
            バッチ実行の入力は、これらのデータセットに格納されます。
            この情報は、Azure ML バッチ実行要求の WebServiceInputs プロパティに渡されます。
            アクティビティの入力では、マップされたデータセットを含める必要があります。 WebServiceInputs は、WebServiceInput で同時には使用できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; WebServiceOutputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; WebServiceOutputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceOutputs" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceOutputs As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.WebServiceOutputs : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceOutputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 キー、値のペアが Azure ML web サービスの出力の名前をデータ ファクトリのデータセットの名前にマッピングします。
            バッチ実行の出力は、これらのデータセットに書き込まれます。
            この情報は、Azure ML バッチ実行要求の webserviceoutputs にあるプロパティに渡されます。
            アクティビティの出力では、マップされたデータセットを含める必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>