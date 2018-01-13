<Type Name="RouteProperties" FullName="Microsoft.Azure.Management.IotHub.Models.RouteProperties">
  <TypeSignature Language="C#" Value="public class RouteProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RouteProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RouteProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RouteProperties" />
  <TypeSignature Language="F#" Value="type RouteProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            IoT ハブを使用してエンドポイントにメッセージをルーティングするルーティング規則のプロパティ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RouteProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RouteProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteProperties (string name, string source, System.Collections.Generic.IList&lt;string&gt; endpointNames, bool isEnabled, string condition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string source, class System.Collections.Generic.IList`1&lt;string&gt; endpointNames, bool isEnabled, string condition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RouteProperties.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String},System.Boolean,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, source As String, endpointNames As IList(Of String), isEnabled As Boolean, Optional condition As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RouteProperties : string * string * System.Collections.Generic.IList&lt;string&gt; * bool * string -&gt; Microsoft.Azure.Management.IotHub.Models.RouteProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.RouteProperties (name, source, endpointNames, isEnabled, condition)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="endpointNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isEnabled" Type="System.Boolean" />
        <Parameter Name="condition" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">ルートの名前。 名前は、英数字、ピリオド、アンダー スコア、ハイフンのみを含めることができます、64 文字の最大長であるおよび一意である必要があります。</param>
        <param name="source">DeviceMessages などに、適用されるルーティング ルールがあるソース。 使用可能な値が含まれます: 'DeviceMessages'、'TwinChangeEvents'、'DeviceLifecycleEvents'、'DeviceJobLifecycleEvents'</param>
        <param name="endpointNames">条件を満たすメッセージのルーティング先エンドポイントのリスト。 現在 1 つのみのエンドポイントは許可されています。</param>
        <param name="isEnabled">ルートが有効になっているかどうかを指定するために使用します。</param>
        <param name="condition">ルーティング規則を適用する評価する条件。 条件を指定しない場合、既定で true と評価します。 文法を参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language</param>
        <summary>
            RouteProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Condition">
      <MemberSignature Language="C#" Value="public string Condition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Condition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RouteProperties.Condition" />
      <MemberSignature Language="VB.NET" Value="Public Property Condition As String" />
      <MemberSignature Language="F#" Value="member this.Condition : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RouteProperties.Condition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="condition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはルーティング規則を適用する評価される条件を設定します。 条件を指定しない場合、既定で true と評価します。
            文法を参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; EndpointNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; EndpointNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RouteProperties.EndpointNames" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EndpointNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RouteProperties.EndpointNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または条件を満たすメッセージのルーティング先エンドポイントのリストを設定します。 現在 1 つのみのエンドポイントは許可されています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RouteProperties.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : bool with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RouteProperties.IsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のルートが有効になっているかどうかを指定するために使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RouteProperties.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RouteProperties.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはルートの名前を設定します。 名前は、英数字、ピリオド、アンダー スコア、ハイフンのみを含めることができます、64 文字の最大長であるおよび一意である必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RouteProperties.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RouteProperties.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または DeviceMessages などに、適用されるルーティング ルールがあるソースを設定します。 使用可能な値が含まれます: 'DeviceMessages'、'TwinChangeEvents'、'DeviceLifecycleEvents'、'DeviceJobLifecycleEvents'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RouteProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="routeProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
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