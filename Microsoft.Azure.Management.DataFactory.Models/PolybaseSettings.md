<Type Name="PolybaseSettings" FullName="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings">
  <TypeSignature Language="C#" Value="public class PolybaseSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolybaseSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class PolybaseSettings" />
  <TypeSignature Language="F#" Value="type PolybaseSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            PolyBase の設定です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolybaseSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.#ctor" />
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
            PolybaseSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolybaseSettings (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string rejectType = null, object rejectValue = null, object rejectSampleValue = null, object useTypeDefault = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string rejectType, object rejectValue, object rejectSampleValue, object useTypeDefault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional rejectType As String = null, Optional rejectValue As Object = null, Optional rejectSampleValue As Object = null, Optional useTypeDefault As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings" Usage="new Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings (additionalProperties, rejectType, rejectValue, rejectSampleValue, useTypeDefault)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="rejectType" Type="System.String" />
        <Parameter Name="rejectValue" Type="System.Object" />
        <Parameter Name="rejectSampleValue" Type="System.Object" />
        <Parameter Name="useTypeDefault" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="rejectType">型を拒否します。 使用可能な値が含まれます 'value'、'percentage'。</param>
        <param name="rejectValue">または、クエリが失敗する前に拒否されることもの行のパーセンテージの値を指定します。 型: 数 (または式 resultType 番号)、最小値: 0。</param>
        <param name="rejectSampleValue">PolyBase が拒否された行の割合を再計算する前に取得しようとする行の数を決定します。 型: 整数 (または式と resultType 整数)、最小値: 0。</param>
        <param name="useTypeDefault">PolyBase がテキスト ファイルからデータを取得する場合にどのように区切りテキスト ファイル内の不足値を処理するかを、指定します。 型: ブール値 (または式の resultType ブール値)。</param>
        <summary>
            PolybaseSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectSampleValue">
      <MemberSignature Language="C#" Value="public object RejectSampleValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RejectSampleValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectSampleValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectSampleValue As Object" />
      <MemberSignature Language="F#" Value="member this.RejectSampleValue : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectSampleValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rejectSampleValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、PolyBase が拒否された行の割合を再計算する前に取得しようとする行の数を決定します。
            型: 整数 (または式と resultType 整数)、最小値: 0。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectType">
      <MemberSignature Language="C#" Value="public string RejectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RejectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectType" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectType As String" />
      <MemberSignature Language="F#" Value="member this.RejectType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rejectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の種類を拒否します。 使用可能な値が含まれます 'value'、'percentage'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectValue">
      <MemberSignature Language="C#" Value="public object RejectValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RejectValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectValue As Object" />
      <MemberSignature Language="F#" Value="member this.RejectValue : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.RejectValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rejectValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、値またはクエリが失敗する前に拒否されることもの行の割合を指定します。 型: 数 (または式 resultType 番号)、最小値: 0。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTypeDefault">
      <MemberSignature Language="C#" Value="public object UseTypeDefault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseTypeDefault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.UseTypeDefault" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTypeDefault As Object" />
      <MemberSignature Language="F#" Value="member this.UseTypeDefault : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings.UseTypeDefault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="useTypeDefault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、PolyBase がテキスト ファイルからデータを取得するときに、区切られたテキスト ファイルに欠損値を処理する方法を指定します。 型: ブール値 (または式の resultType ブール値)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>