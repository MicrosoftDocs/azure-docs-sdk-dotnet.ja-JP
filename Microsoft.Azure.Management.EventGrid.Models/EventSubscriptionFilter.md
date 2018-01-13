<Type Name="EventSubscriptionFilter" FullName="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter">
  <TypeSignature Language="C#" Value="public class EventSubscriptionFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventSubscriptionFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class EventSubscriptionFilter" />
  <TypeSignature Language="F#" Value="type EventSubscriptionFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            イベント サブスクリプションのフィルター
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventSubscriptionFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            EventSubscriptionFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventSubscriptionFilter (string subjectBeginsWith = null, string subjectEndsWith = null, System.Collections.Generic.IList&lt;string&gt; includedEventTypes = null, Nullable&lt;bool&gt; isSubjectCaseSensitive = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string subjectBeginsWith, string subjectEndsWith, class System.Collections.Generic.IList`1&lt;string&gt; includedEventTypes, valuetype System.Nullable`1&lt;bool&gt; isSubjectCaseSensitive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional subjectBeginsWith As String = null, Optional subjectEndsWith As String = null, Optional includedEventTypes As IList(Of String) = null, Optional isSubjectCaseSensitive As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter : string * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter" Usage="new Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter (subjectBeginsWith, subjectEndsWith, includedEventTypes, isSubjectCaseSensitive)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="subjectBeginsWith" Type="System.String" />
        <Parameter Name="subjectEndsWith" Type="System.String" />
        <Parameter Name="includedEventTypes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isSubjectCaseSensitive" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="subjectBeginsWith">リソースのパス プレフィックスに基づくイベント サブスクリプションのイベントをフィルター処理する省略可能な文字列。
            この形式は、イベントの発行元によって異なります。
            ワイルドカード文字は、このパスではサポートされません。</param>
        <param name="subjectEndsWith">リソース パスのサフィックスに基づくイベント サブスクリプションのイベントをフィルター処理する省略可能な文字列。
            ワイルドカード文字は、このパスではサポートされません。</param>
        <param name="includedEventTypes">イベント サブスクリプションの一部である必要がある該当するイベントの種類の一覧。
            すべての種類のイベントをサブスクライブする場合は、"all"の文字列をこのリスト内の要素として指定する必要があります。</param>
        <param name="isSubjectCaseSensitive">フィルターの SubjectBeginsWith および SubjectEndsWith プロパティが大文字小文字を区別の方法で比較するかどうかを指定します。</param>
        <summary>
            EventSubscriptionFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludedEventTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IncludedEventTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IncludedEventTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.IncludedEventTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludedEventTypes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IncludedEventTypes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.IncludedEventTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="includedEventTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベント サブスクリプションの一部である必要がある該当するイベントの種類の一覧を設定します。
            すべての種類のイベントをサブスクライブする場合は、"all"の文字列をこのリスト内の要素として指定する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSubjectCaseSensitive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSubjectCaseSensitive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSubjectCaseSensitive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.IsSubjectCaseSensitive" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSubjectCaseSensitive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSubjectCaseSensitive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.IsSubjectCaseSensitive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isSubjectCaseSensitive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、フィルターの SubjectBeginsWith および SubjectEndsWith プロパティが大文字小文字を区別の方法で比較するかどうかを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubjectBeginsWith">
      <MemberSignature Language="C#" Value="public string SubjectBeginsWith { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubjectBeginsWith" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.SubjectBeginsWith" />
      <MemberSignature Language="VB.NET" Value="Public Property SubjectBeginsWith As String" />
      <MemberSignature Language="F#" Value="member this.SubjectBeginsWith : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.SubjectBeginsWith" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subjectBeginsWith")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースのパス プレフィックスに基づくイベント サブスクリプションのイベントをフィルター処理する任意の文字列を設定します。
            この形式は、イベントの発行元によって異なります。
            ワイルドカード文字は、このパスではサポートされません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubjectEndsWith">
      <MemberSignature Language="C#" Value="public string SubjectEndsWith { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubjectEndsWith" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.SubjectEndsWith" />
      <MemberSignature Language="VB.NET" Value="Public Property SubjectEndsWith As String" />
      <MemberSignature Language="F#" Value="member this.SubjectEndsWith : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.SubjectEndsWith" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subjectEndsWith")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソース パスのサフィックスに基づくイベント サブスクリプションのイベントをフィルター処理する任意の文字列を設定します。
            ワイルドカード文字は、このパスではサポートされません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>