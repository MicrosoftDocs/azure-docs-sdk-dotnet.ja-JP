<Type Name="FallbackRouteProperties" FullName="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties">
  <TypeSignature Language="C#" Value="public class FallbackRouteProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi FallbackRouteProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class FallbackRouteProperties" />
  <TypeSignature Language="F#" Value="type FallbackRouteProperties = class" />
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
            フォールバックのルートのプロパティです。 IoT Hub は、代替のエンドポイントにメッセージをルーティングするときに、これらのプロパティを使用します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FallbackRouteProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FallbackRouteProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FallbackRouteProperties (System.Collections.Generic.IList&lt;string&gt; endpointNames, bool isEnabled, string condition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; endpointNames, bool isEnabled, string condition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.#ctor(System.Collections.Generic.IList{System.String},System.Boolean,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointNames As IList(Of String), isEnabled As Boolean, Optional condition As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties : System.Collections.Generic.IList&lt;string&gt; * bool * string -&gt; Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties (endpointNames, isEnabled, condition)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isEnabled" Type="System.Boolean" />
        <Parameter Name="condition" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointNames">条件を満たすメッセージのルーティング先エンドポイントのリスト。 現在 1 つのみのエンドポイントは許可されています。</param>
        <param name="isEnabled">フォールバックのルートが有効になっているかどうかを指定するために使用します。</param>
        <param name="condition">フォールバックのルートを適用するために評価される条件です。 条件指定しない場合は true に評価されます既定です。 文法を参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language</param>
        <summary>
            FallbackRouteProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Condition">
      <MemberSignature Language="C#" Value="public string Condition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Condition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.Condition" />
      <MemberSignature Language="VB.NET" Value="Public Property Condition As String" />
      <MemberSignature Language="F#" Value="member this.Condition : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.Condition" />
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
            取得またはフォールバックのルートを適用するために評価される条件を設定します。 条件指定しない場合は true に評価されます既定です。 文法を参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; EndpointNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; EndpointNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.EndpointNames" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EndpointNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.EndpointNames" />
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
            取得または設定する条件を満たすメッセージのルーティング先エンドポイントの一覧。 現在 1 つのみのエンドポイントは許可されています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : bool with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.IsEnabled" />
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
            取得または設定フォールバックのルートが有効になっているかどうかを指定するために使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public static string Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.Source" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string" Usage="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.Source" />
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
            ルーティング規則を適用するソースです。 たとえば、DeviceMessages
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fallbackRouteProperties.Validate " />
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