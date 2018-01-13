<Type Name="IfConditionActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity">
  <TypeSignature Language="C#" Value="public class IfConditionActivity : Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IfConditionActivity extends Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class IfConditionActivity&#xA;Inherits ControlActivity" />
  <TypeSignature Language="F#" Value="type IfConditionActivity = class&#xA;    inherit ControlActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ControlActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("IfCondition")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            このアクティビティは、ブール式を評価し、ifTrueActivities プロパティの下のアクティビティまたは式の結果に応じて、ifFalseActivities プロパティのいずれかを実行します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IfConditionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.#ctor" />
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
            IfConditionActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IfConditionActivity (string name, Microsoft.Azure.Management.DataFactory.Models.Expression expression, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; ifTrueActivities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; ifFalseActivities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactory.Models.Expression expression, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; ifTrueActivities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; ifFalseActivities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.#ctor(System.String,Microsoft.Azure.Management.DataFactory.Models.Expression,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.Activity},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.Activity})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity : string * Microsoft.Azure.Management.DataFactory.Models.Expression * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity (name, expression, additionalProperties, description, dependsOn, ifTrueActivities, ifFalseActivities)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="expression" Type="Microsoft.Azure.Management.DataFactory.Models.Expression" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="ifTrueActivities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;" />
        <Parameter Name="ifFalseActivities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;" />
      </Parameters>
      <Docs>
        <param name="name">アクティビティ名。</param>
        <param name="expression">ブール値に評価する式。 これについては、実行されるアクティビティ (ifTrueActivities または ifFalseActivities) のブロックを決定に使用します。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="description">アクティビティの説明です。</param>
        <param name="dependsOn">アクティビティは、条件によって異なります。</param>
        <param name="ifTrueActivities">式が評価される場合に実行されるアクティビティのリストを true にします。 これは省略可能なプロパティと、指定しないと、操作をしなくても、アクティビティが終了します。</param>
        <param name="ifFalseActivities">式が false に評価される場合に実行されるアクティビティのリスト。 これは省略可能なプロパティと、指定しないと、操作をしなくても、アクティビティが終了します。</param>
        <summary>
            IfConditionActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.Expression Expression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.Expression Expression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.Expression" />
      <MemberSignature Language="VB.NET" Value="Public Property Expression As Expression" />
      <MemberSignature Language="F#" Value="member this.Expression : Microsoft.Azure.Management.DataFactory.Models.Expression with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.Expression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.expression")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.Expression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはブール値に評価される式を設定します。 これについては、実行されるアクティビティ (ifTrueActivities または ifFalseActivities) のブロックを決定に使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfFalseActivities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; IfFalseActivities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; IfFalseActivities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.IfFalseActivities" />
      <MemberSignature Language="VB.NET" Value="Public Property IfFalseActivities As IList(Of Activity)" />
      <MemberSignature Language="F#" Value="member this.IfFalseActivities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.IfFalseActivities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.ifFalseActivities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または式が false に評価される場合に実行されるアクティビティのリストを設定します。 これは省略可能なプロパティと、指定しないと、操作をしなくても、アクティビティが終了します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfTrueActivities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; IfTrueActivities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; IfTrueActivities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.IfTrueActivities" />
      <MemberSignature Language="VB.NET" Value="Public Property IfTrueActivities As IList(Of Activity)" />
      <MemberSignature Language="F#" Value="member this.IfTrueActivities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.IfTrueActivities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.ifTrueActivities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または式が評価される場合に実行されるアクティビティの一覧の設定を true にします。 これは省略可能なプロパティと、指定しないと、操作をしなくても、アクティビティが終了します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IfConditionActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="ifConditionActivity.Validate " />
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