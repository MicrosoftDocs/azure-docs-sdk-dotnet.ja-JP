<Type Name="LogProfileResourcePatch" FullName="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch">
  <TypeSignature Language="C#" Value="public class LogProfileResourcePatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LogProfileResourcePatch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch" />
  <TypeSignature Language="VB.NET" Value="Public Class LogProfileResourcePatch" />
  <TypeSignature Language="F#" Value="type LogProfileResourcePatch = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Patch 操作のログ プロファイル リソースです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LogProfileResourcePatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            LogProfileResourcePatch クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LogProfileResourcePatch (System.Collections.Generic.IList&lt;string&gt; locations, System.Collections.Generic.IList&lt;string&gt; categories, Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy retentionPolicy, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string storageAccountId = null, string serviceBusRuleId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;string&gt; categories, class Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy retentionPolicy, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string storageAccountId, string serviceBusRuleId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch (locations, categories, retentionPolicy, tags, storageAccountId, serviceBusRuleId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="categories" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="retentionPolicy" Type="Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="serviceBusRuleId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="locations">アクティビティ ログのイベントを格納する、またはストリーミングの地域の一覧です。 これは、'global' の場所を含む有効な ARM 場所のコンマ区切りリストです。</param>
        <param name="categories">ログのカテゴリ。 ユーザーには便利では、これらのカテゴリが作成されます。 一部の値が: '書き込み'、'Delete'、または 'Action'</param>
        <param name="retentionPolicy">ログ内のイベントの保有期間ポリシー。</param>
        <param name="tags">リソース タグ</param>
        <param name="storageAccountId">アクティビティ ログの送信にストレージ アカウントのリソース id です。</param>
        <param name="serviceBusRuleId">するには、動作状況ログのストリーミング用に作成されたイベント ハブがある service bus 名前空間のサービス バス ルール ID。 ID が形式では、ルール: ' {サービス バス リソース ID}/authorizationrules/{キー名}'。</param>
        <summary>
            LogProfileResourcePatch クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Categories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Categories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Categories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Categories" />
      <MemberSignature Language="VB.NET" Value="Public Property Categories As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Categories : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Categories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.categories")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはログのカテゴリを設定します。 ユーザーには便利では、これらのカテゴリが作成されます。 一部の値が: '書き込み'、'Delete'、または 'Action'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Locations" />
      <MemberSignature Language="VB.NET" Value="Public Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または地域をアクティビティのログ イベントを格納する、またはストリーミングの一覧を設定します。 これは、'global' の場所を含む有効な ARM 場所のコンマ区切りリストです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As RetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.RetentionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはログにイベントの保有ポリシーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusRuleId">
      <MemberSignature Language="C#" Value="public string ServiceBusRuleId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusRuleId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.ServiceBusRuleId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusRuleId As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusRuleId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.ServiceBusRuleId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusRuleId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定をするには、動作状況ログのストリーミング用に作成されたイベント ハブがある service bus 名前空間の service bus ルール ID。 ID が形式では、ルール: ' {サービス バス リソース ID}/authorizationrules/{キー名}'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountId">
      <MemberSignature Language="C#" Value="public string StorageAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.StorageAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.StorageAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアクティビティ ログの送信にストレージ アカウントのリソース id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソース タグを設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="logProfileResourcePatch.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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