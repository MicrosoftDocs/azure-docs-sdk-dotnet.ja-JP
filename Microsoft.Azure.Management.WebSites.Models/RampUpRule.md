<Type Name="RampUpRule" FullName="Microsoft.Azure.Management.WebSites.Models.RampUpRule">
  <TypeSignature Language="C#" Value="public class RampUpRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RampUpRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RampUpRule" />
  <TypeSignature Language="VB.NET" Value="Public Class RampUpRule" />
  <TypeSignature Language="F#" Value="type RampUpRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            テストの準備のルールをルーティングします。 このルールが使用するは、静的なトラフィック % をスロットにリダイレクトする、またはパフォーマンスに基づくルーティングの % を徐々 に変化します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RampUpRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RampUpRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RampUpRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RampUpRule (string actionHostName = null, Nullable&lt;double&gt; reroutePercentage = null, Nullable&lt;double&gt; changeStep = null, Nullable&lt;int&gt; changeIntervalInMinutes = null, Nullable&lt;double&gt; minReroutePercentage = null, Nullable&lt;double&gt; maxReroutePercentage = null, string changeDecisionCallbackUrl = null, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string actionHostName, valuetype System.Nullable`1&lt;float64&gt; reroutePercentage, valuetype System.Nullable`1&lt;float64&gt; changeStep, valuetype System.Nullable`1&lt;int32&gt; changeIntervalInMinutes, valuetype System.Nullable`1&lt;float64&gt; minReroutePercentage, valuetype System.Nullable`1&lt;float64&gt; maxReroutePercentage, string changeDecisionCallbackUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RampUpRule.#ctor(System.String,System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional actionHostName As String = null, Optional reroutePercentage As Nullable(Of Double) = null, Optional changeStep As Nullable(Of Double) = null, Optional changeIntervalInMinutes As Nullable(Of Integer) = null, Optional minReroutePercentage As Nullable(Of Double) = null, Optional maxReroutePercentage As Nullable(Of Double) = null, Optional changeDecisionCallbackUrl As String = null, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RampUpRule : string * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.RampUpRule" Usage="new Microsoft.Azure.Management.WebSites.Models.RampUpRule (actionHostName, reroutePercentage, changeStep, changeIntervalInMinutes, minReroutePercentage, maxReroutePercentage, changeDecisionCallbackUrl, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionHostName" Type="System.String" />
        <Parameter Name="reroutePercentage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="changeStep" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="changeIntervalInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minReroutePercentage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maxReroutePercentage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="changeDecisionCallbackUrl" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actionHostName">した場合に、トラフィックがリダイレクトされますスロットのホスト名です。 例: 
            myapp stage.azurewebsites.net です。</param>
        <param name="reroutePercentage">リダイレクトされるトラフィックの割合&lt;コード&gt;ActionHostName&lt;/code&gt;です。</param>
        <param name="changeStep">自動増加のシナリオでは、ステップからの追加/削除するには&lt;コード&gt;ReroutePercentage&lt;/code&gt;に達するまで&lt;コード&gt;MinReroutePercentage&lt;/code&gt;または&lt;コード&gt;MaxReroutePercentage&lt;/code&gt;です。 時間ごとに特定のサイトのメトリックがチェックされて&lt;コード&gt;ChangeIntervalInMinutes&lt;/code&gt;です。
            TiPCallback のサイト拡張機能で指定できる URL でカスタム デシジョン アルゴリズムを指定することができます&lt;コード&gt;ChangeDecisionCallbackUrl&lt;/code&gt;です。</param>
        <param name="changeIntervalInMinutes">ReroutePercentage の再評価 mimuntes の間隔を指定します。</param>
        <param name="minReroutePercentage">下位の境界上 ReroutePercentage が存在するを指定します。</param>
        <param name="maxReroutePercentage">上限の境界下 ReroutePercentage が存在するを指定します。</param>
        <param name="changeDecisionCallbackUrl">URL を指定することが TiPCallback サイト拡張機能では、カスタム デシジョン アルゴリズムを指定できます。 Scaffold とコントラクトの TiPCallback サイト拡張機能を参照してください。
            https://www.siteextensions.net/packages/TiPCallback/</param>
        <param name="name">ルーティング ルールの名前です。 推奨される名前は、この実験でトラフィックを受信するスロットをポイントすることです。</param>
        <summary>
            RampUpRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionHostName">
      <MemberSignature Language="C#" Value="public string ActionHostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.ActionHostName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionHostName As String" />
      <MemberSignature Language="F#" Value="member this.ActionHostName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.ActionHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定することにした場合、トラフィックはリダイレクトされますスロットのホスト名。 例:  myapp stage.azurewebsites.net です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeDecisionCallbackUrl">
      <MemberSignature Language="C#" Value="public string ChangeDecisionCallbackUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ChangeDecisionCallbackUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeDecisionCallbackUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ChangeDecisionCallbackUrl As String" />
      <MemberSignature Language="F#" Value="member this.ChangeDecisionCallbackUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeDecisionCallbackUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeDecisionCallbackUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            TiPCallback でカスタム デシジョン アルゴリズムを指定することができますを取得または設定はサイトの URL を指定することが拡張機能です。 Scaffold とコントラクトの TiPCallback サイト拡張機能を参照してください。
            https://www.siteextensions.net/packages/TiPCallback/
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeIntervalInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ChangeIntervalInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ChangeIntervalInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeIntervalInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property ChangeIntervalInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ChangeIntervalInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeIntervalInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeIntervalInMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 mimuntes ReroutePercentage の再評価間隔を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeStep">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ChangeStep { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ChangeStep" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeStep" />
      <MemberSignature Language="VB.NET" Value="Public Property ChangeStep As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ChangeStep : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.ChangeStep" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeStep")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            自動増加からの追加/削除するには、手順は、このシナリオで取得または設定&amp;lt; コード&amp;gt;ReroutePercentage&amp;lt;/code&amp;gt; に達するまで&amp;lt; コード&amp;gt;MinReroutePercentage&amp;lt;/code&amp;gt; または&amp;lt; コード&amp;gt;MaxReroutePercentage&amp;lt;/code&amp;gt;。 時間ごとに特定のサイトのメトリックがチェックされて&amp;lt; コード&amp;gt;ChangeIntervalInMinutes&amp;lt;/code&amp;gt;。
            TiPCallback のサイト拡張機能で指定できる URL でカスタム デシジョン アルゴリズムを指定することができます&amp;lt; コード&amp;gt;ChangeDecisionCallbackUrl&amp;lt;/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReroutePercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MaxReroutePercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MaxReroutePercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.MaxReroutePercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReroutePercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MaxReroutePercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.MaxReroutePercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxReroutePercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、上限の境界下 ReroutePercentage が存在するを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReroutePercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinReroutePercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinReroutePercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.MinReroutePercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinReroutePercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinReroutePercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.MinReroutePercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minReroutePercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、下位の境界上 ReroutePercentage が存在するを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            取得またはルーティングの規則の名前を設定します。 推奨される名前は、この実験でトラフィックを受信するスロットをポイントすることです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReroutePercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ReroutePercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ReroutePercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RampUpRule.ReroutePercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property ReroutePercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ReroutePercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RampUpRule.ReroutePercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reroutePercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定にリダイレクトされるトラフィックの割合&amp;lt; コード&amp;gt;ActionHostName&amp;lt;/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>