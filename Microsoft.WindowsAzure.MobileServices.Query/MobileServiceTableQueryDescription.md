<Type Name="MobileServiceTableQueryDescription" FullName="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class MobileServiceTableQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MobileServiceTableQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MobileServiceTableQueryDescription" />
  <TypeSignature Language="F#" Value="type MobileServiceTableQueryDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            使用して OData のサブセットに対するモバイル サービスのクエリ構造体の要素を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceTableQueryDescription (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription : string -&gt; Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" Usage="new Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription tableName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">To be added.</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As MobileServiceTableQueryDescription" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" Usage="mobileServiceTableQueryDescription.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            コピーを作成します。<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /></summary>
        <returns>複製されたクエリ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.QueryNode Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Query.QueryNode Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As QueryNode" />
      <MemberSignature Language="F#" Value="member this.Filter : Microsoft.WindowsAzure.MobileServices.Query.QueryNode with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクエリのフィルター式を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeTotalCount">
      <MemberSignature Language="C#" Value="public bool IncludeTotalCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeTotalCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.IncludeTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeTotalCount As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeTotalCount : bool with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.IncludeTotalCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクエリで返された場合は、サーバーがデータの上限を強制していないすべてのレコードの合計数を要求すべきかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ordering">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.MobileServices.Query.OrderByNode&gt; Ordering { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.MobileServices.Query.OrderByNode&gt; Ordering" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Ordering" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Ordering As IList(Of OrderByNode)" />
      <MemberSignature Language="F#" Value="member this.Ordering : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.MobileServices.Query.OrderByNode&gt;" Usage="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Ordering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.MobileServices.Query.OrderByNode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クエリの順序付けの制約を指定する式の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parse">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription Parse (string tableName, string query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription Parse(string tableName, string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Parse(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Parse (tableName As String, query As String) As MobileServiceTableQueryDescription" />
      <MemberSignature Language="F#" Value="static member Parse : string * string -&gt; Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" Usage="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Parse (tableName, query)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">クエリのテーブルの名前。</param>
        <param name="query">Odata のクエリ文字列</param>
        <summary>
            OData のクエリを解析し、作成、<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" />インスタンス
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /> のインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Selection">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Selection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Selection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Selection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Selection As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Selection : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Selection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            テーブル内の項目から選択する必要があるフィールドの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Skip { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Skip" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Skip" />
      <MemberSignature Language="VB.NET" Value="Public Property Skip As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Skip : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Skip" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスキップする要素の数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.TableName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string" Usage="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクエリ対象のテーブルの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToODataString">
      <MemberSignature Language="C#" Value="public string ToODataString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ToODataString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.ToODataString" />
      <MemberSignature Language="VB.NET" Value="Public Function ToODataString () As String" />
      <MemberSignature Language="F#" Value="member this.ToODataString : unit -&gt; string" Usage="mobileServiceTableQueryDescription.ToODataString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            クエリの構造をクエリの標準的な OData URI プロトコルに変換します。
            </summary>
        <returns>
            クエリを表す URI フラグメント。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription.Top" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または取得する要素の数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>