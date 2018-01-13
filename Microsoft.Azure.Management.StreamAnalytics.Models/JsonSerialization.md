<Type Name="JsonSerialization" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization">
  <TypeSignature Language="C#" Value="public class JsonSerialization : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JsonSerialization extends Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonSerialization&#xA;Inherits Serialization" />
  <TypeSignature Language="F#" Value="type JsonSerialization = class&#xA;    inherit Serialization" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.Serialization</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Json")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            入力からのデータをシリアル化する方法または JSON 形式で出力に書き込まれるときにデータをシリアル化する方法について説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonSerialization ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JsonSerialization クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonSerialization (string encoding = null, string format = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string encoding, string format) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional encoding As String = null, Optional format As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization : string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization (encoding, format)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="encoding" Type="System.String" />
        <Parameter Name="format" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="encoding">入力の場合、受信データのエンコードと出力の場合、送信データのエンコードを指定します。 PUT (CreateOrReplace) 要求に必要です。 使用可能な値が含まれます: 'UTF8'</param>
        <param name="format">このプロパティは、出力のみの JSON のシリアル化にのみ適用されます。 これは入力に適用されません。 このプロパティは、出力で使用する JSON の形式を指定します。 現在サポートされている値は、各 JSON オブジェクトを新しい行と JSON オブジェクトの配列として出力をフォーマットすることを示す 'array' で区切って使用して出力をフォーマットすることを示す' lineSeparated' です。 既定値は 'lineSeparated' null のままにします。 使用可能な値が含まれます: 'LineSeparated'、'Array'</param>
        <summary>
            JsonSerialization クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoding">
      <MemberSignature Language="C#" Value="public string Encoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Encoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.Encoding" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoding As String" />
      <MemberSignature Language="F#" Value="member this.Encoding : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.Encoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encoding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、入力の場合、受信データのエンコードと出力の場合、送信データのエンコードを指定します。 PUT (CreateOrReplace) 要求に必要です。 使用可能な値が含まれます: 'UTF8'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public string Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As String" />
      <MemberSignature Language="F#" Value="member this.Format : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、このプロパティは出力のみの JSON のシリアル化にのみ適用されます。 これは入力に適用されません。 このプロパティは、出力で使用する JSON の形式を指定します。 現在サポートされている値は、各 JSON オブジェクトを新しい行と JSON オブジェクトの配列として出力をフォーマットすることを示す 'array' で区切って使用して出力をフォーマットすることを示す' lineSeparated' です。 既定値は 'lineSeparated' null のままにします。 使用可能な値が含まれます: 'LineSeparated'、'Array'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>