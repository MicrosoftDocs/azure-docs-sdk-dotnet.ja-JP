<Type Name="DeploymentProperties" FullName="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties">
  <TypeSignature Language="C#" Value="public class DeploymentProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentProperties" />
  <TypeSignature Language="F#" Value="type DeploymentProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            配置プロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DeploymentProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentProperties (Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode mode, object template = null, Microsoft.Azure.Management.ResourceManager.Models.TemplateLink templateLink = null, object parameters = null, Microsoft.Azure.Management.ResourceManager.Models.ParametersLink parametersLink = null, Microsoft.Azure.Management.ResourceManager.Models.DebugSetting debugSetting = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode mode, object template, class Microsoft.Azure.Management.ResourceManager.Models.TemplateLink templateLink, object parameters, class Microsoft.Azure.Management.ResourceManager.Models.ParametersLink parametersLink, class Microsoft.Azure.Management.ResourceManager.Models.DebugSetting debugSetting) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.#ctor(Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode,System.Object,Microsoft.Azure.Management.ResourceManager.Models.TemplateLink,System.Object,Microsoft.Azure.Management.ResourceManager.Models.ParametersLink,Microsoft.Azure.Management.ResourceManager.Models.DebugSetting)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties : Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode * obj * Microsoft.Azure.Management.ResourceManager.Models.TemplateLink * obj * Microsoft.Azure.Management.ResourceManager.Models.ParametersLink * Microsoft.Azure.Management.ResourceManager.Models.DebugSetting -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties" Usage="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties (mode, template, templateLink, parameters, parametersLink, debugSetting)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mode" Type="Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode" />
        <Parameter Name="template" Type="System.Object" />
        <Parameter Name="templateLink" Type="Microsoft.Azure.Management.ResourceManager.Models.TemplateLink" />
        <Parameter Name="parameters" Type="System.Object" />
        <Parameter Name="parametersLink" Type="Microsoft.Azure.Management.ResourceManager.Models.ParametersLink" />
        <Parameter Name="debugSetting" Type="Microsoft.Azure.Management.ResourceManager.Models.DebugSetting" />
      </Parameters>
      <Docs>
        <param name="mode">リソースをデプロイに使用されるモードです。 この値は、増分または完了のいずれかを指定できます。 Incremental モードでは、リソースは、テンプレートに含まれていない既存のリソースを削除することがなく展開されます。 完全なモードでリソースがデプロイされ、テンプレートに含まれていないリソース グループ内の既存のリソースが削除されます。 リソースを削除することが意図せずに、完全なモードを使用する場合は注意します。 使用可能な値が含まれます: '増分'、'完了'</param>
        <param name="template">テンプレートの内容。 既存のテンプレートにリンクするのではなく、要求で直接テンプレートの構文を渡す場合は、この要素を使用します。 JObject または適切な形式の JSON 文字列を指定できます。 TemplateLink プロパティと、テンプレート プロパティの両方ではなくはどちらかを使用します。</param>
        <param name="templateLink">テンプレートの URI。 TemplateLink プロパティと、テンプレート プロパティの両方ではなくはどちらかを使用します。</param>
        <param name="parameters">テンプレートのデプロイのパラメーターを定義する名前と値のペア。 既存のパラメーター ファイルへのリンクではなく、要求で直接パラメーター値を指定する場合は、この要素を使用します。 ParametersLink プロパティと、パラメーター プロパティの両方ではなくはどちらかを使用します。
            JObject または適切な形式の JSON 文字列を指定できます。</param>
        <param name="parametersLink">パラメーター ファイルの URI。 既存のパラメーター ファイルにリンクするには、この要素を使用します。 ParametersLink プロパティと、パラメーター プロパティの両方ではなくはどちらかを使用します。</param>
        <param name="debugSetting">展開のデバッグ設定です。</param>
        <summary>
            DeploymentProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DebugSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.DebugSetting DebugSetting { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.DebugSetting DebugSetting" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.DebugSetting" />
      <MemberSignature Language="VB.NET" Value="Public Property DebugSetting As DebugSetting" />
      <MemberSignature Language="F#" Value="member this.DebugSetting : Microsoft.Azure.Management.ResourceManager.Models.DebugSetting with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.DebugSetting" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="debugSetting")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DebugSetting</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または展開のデバッグ設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As DeploymentMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースをデプロイに使用されるモードを設定します。 この値は、増分または完了のいずれかを指定できます。 Incremental モードでは、リソースは、テンプレートに含まれていない既存のリソースを削除することがなく展開されます。 完全なモードでリソースがデプロイされ、テンプレートに含まれていないリソース グループ内の既存のリソースが削除されます。 リソースを削除することが意図せずに、完全なモードを使用する場合は注意します。 使用可能な値が含まれます: '増分'、'完了'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public object Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As Object" />
      <MemberSignature Language="F#" Value="member this.Parameters : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはテンプレートのデプロイのパラメーターを定義する名前と値のペアを設定します。 既存のパラメーター ファイルへのリンクではなく、要求で直接パラメーター値を指定する場合は、この要素を使用します。 ParametersLink プロパティと、パラメーター プロパティの両方ではなくはどちらかを使用します。 JObject または適切な形式の JSON 文字列を指定できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParametersLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ParametersLink ParametersLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ParametersLink ParametersLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.ParametersLink" />
      <MemberSignature Language="VB.NET" Value="Public Property ParametersLink As ParametersLink" />
      <MemberSignature Language="F#" Value="member this.ParametersLink : Microsoft.Azure.Management.ResourceManager.Models.ParametersLink with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.ParametersLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parametersLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ParametersLink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパラメーター ファイルの URI を設定します。 既存のパラメーター ファイルにリンクするには、この要素を使用します。 ParametersLink プロパティと、パラメーター プロパティの両方ではなくはどちらかを使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Template">
      <MemberSignature Language="C#" Value="public object Template { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Template" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Template" />
      <MemberSignature Language="VB.NET" Value="Public Property Template As Object" />
      <MemberSignature Language="F#" Value="member this.Template : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Template" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="template")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはテンプレートの内容を設定します。 既存のテンプレートにリンクするのではなく、要求で直接テンプレートの構文を渡す場合は、この要素を使用します。 JObject または適切な形式の JSON 文字列を指定できます。 TemplateLink プロパティと、テンプレート プロパティの両方ではなくはどちらかを使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TemplateLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.TemplateLink TemplateLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.TemplateLink TemplateLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.TemplateLink" />
      <MemberSignature Language="VB.NET" Value="Public Property TemplateLink As TemplateLink" />
      <MemberSignature Language="F#" Value="member this.TemplateLink : Microsoft.Azure.Management.ResourceManager.Models.TemplateLink with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.TemplateLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="templateLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.TemplateLink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはテンプレートの URI を設定します。 TemplateLink プロパティと、テンプレート プロパティの両方ではなくはどちらかを使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deploymentProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
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