<Type Name="TableQuery" FullName="Microsoft.WindowsAzure.Storage.Table.TableQuery">
  <TypeSignature Language="C#" Value="public class TableQuery" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableQuery extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />
  <TypeSignature Language="VB.NET" Value="Public Class TableQuery" />
  <TypeSignature Language="F#" Value="type TableQuery = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            指定されたテーブルに対するクエリを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            指定されたテーブルに対するクエリを表します。
            </summary>
        <remarks>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスは、クエリが実行されるときに使用するクエリ パラメーターを集計します。 1 つ、 <c>executeQuery</c>または<c>executeQuerySegmented</c>メソッドの<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />クエリの実行に呼び出す必要があります。 パラメーターはエンコードされ、テーブルのクエリを実行すると、サーバーに渡されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CombineFilters">
      <MemberSignature Language="C#" Value="public static string CombineFilters (string filterA, string operatorString, string filterB);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CombineFilters(string filterA, string operatorString, string filterB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.CombineFilters(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CombineFilters (filterA As String, operatorString As String, filterB As String) As String" />
      <MemberSignature Language="F#" Value="static member CombineFilters : string * string * string -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.CombineFilters (filterA, operatorString, filterB)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filterA" Type="System.String" />
        <Parameter Name="operatorString" Type="System.String" />
        <Parameter Name="filterB" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filterA">最初の書式付きフィルター条件を含む文字列。</param>
        <param name="operatorString">(AND、OR) を使用する演算子を含む文字列。</param>
        <param name="filterB">2 番目の書式付きフィルター条件を含む文字列。</param>
        <summary>
            2 つのフィルター条件に指定された論理演算子を使用してフィルター条件を作成します。
            </summary>
        <returns>結合されたフィルター式を含む文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Copy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery Copy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery Copy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.Copy" />
      <MemberSignature Language="VB.NET" Value="Public Function Copy () As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Copy : unit -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery" Usage="tableQuery.Copy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterString">
      <MemberSignature Language="C#" Value="public string FilterString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableQuery.FilterString" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterString As String" />
      <MemberSignature Language="F#" Value="member this.FilterString : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.FilterString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはテーブルのクエリで使用するフィルター式を設定します。
            </summary>
        <value>クエリで使用するフィルター式を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterCondition">
      <MemberSignature Language="C#" Value="public static string GenerateFilterCondition (string propertyName, string operation, string givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterCondition(string propertyName, string operation, string givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterCondition(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterCondition (propertyName As String, operation As String, givenValue As String) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterCondition : string * string * string -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterCondition (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">比較するプロパティの名前を含む文字列。</param>
        <param name="operation">使用する比較演算子を含む文字列。</param>
        <param name="givenValue">プロパティと比較する値を含む文字列。</param>
        <summary>
            文字列値のプロパティ フィルター条件文字列を生成します。
            </summary>
        <returns>書式付きフィルター条件を表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForBinary">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForBinary (string propertyName, string operation, byte[] givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForBinary(string propertyName, string operation, unsigned int8[] givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForBinary(System.String,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForBinary (propertyName As String, operation As String, givenValue As Byte()) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForBinary : string * string * byte[] -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForBinary (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="propertyName">比較するプロパティの名前を含む文字列。</param>
        <param name="operation">使用する比較演算子を含む文字列。</param>
        <param name="givenValue">プロパティと比較する値を含むバイト配列。</param>
        <summary>
            バイナリ値のプロパティ フィルター条件文字列を生成します。
            </summary>
        <returns>書式付きフィルター条件を表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForBool">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForBool (string propertyName, string operation, bool givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForBool(string propertyName, string operation, bool givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForBool(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForBool (propertyName As String, operation As String, givenValue As Boolean) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForBool : string * string * bool -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForBool (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="propertyName">比較するプロパティの名前を含む文字列。</param>
        <param name="operation">使用する比較演算子を含む文字列。</param>
        <param name="givenValue">A <c>bool</c>プロパティと比較する値を含むです。</param>
        <summary>
            プロパティ フィルター条件文字列をブール値を生成します。
            </summary>
        <returns>書式付きフィルター条件を表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForDate">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForDate (string propertyName, string operation, DateTimeOffset givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForDate(string propertyName, string operation, valuetype System.DateTimeOffset givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForDate(System.String,System.String,System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForDate (propertyName As String, operation As String, givenValue As DateTimeOffset) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForDate : string * string * DateTimeOffset -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForDate (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="propertyName">比較するプロパティの名前を含む文字列。</param>
        <param name="operation">使用する比較演算子を含む文字列。</param>
        <param name="givenValue">A<see cref="T:System.DateTimeOffset" />プロパティと比較する値を含むです。</param>
        <summary>
            プロパティ フィルター条件文字列を生成、<see cref="T:System.DateTimeOffset" />値。
            </summary>
        <returns>書式付きフィルター条件を表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForDouble">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForDouble (string propertyName, string operation, double givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForDouble(string propertyName, string operation, float64 givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForDouble(System.String,System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForDouble (propertyName As String, operation As String, givenValue As Double) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForDouble : string * string * double -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForDouble (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="propertyName">比較するプロパティの名前を含む文字列。</param>
        <param name="operation">使用する比較演算子を含む文字列。</param>
        <param name="givenValue">A<see cref="T:System.Double" />プロパティと比較する値を含むです。</param>
        <summary>
            プロパティ フィルター条件文字列を生成、<see cref="T:System.Double" />値。
            </summary>
        <returns>書式付きフィルター条件を表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForGuid">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForGuid (string propertyName, string operation, Guid givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForGuid(string propertyName, string operation, valuetype System.Guid givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForGuid(System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForGuid (propertyName As String, operation As String, givenValue As Guid) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForGuid : string * string * Guid -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForGuid (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="propertyName">比較するプロパティの名前を含む文字列。</param>
        <param name="operation">使用する比較演算子を含む文字列。</param>
        <param name="givenValue">A<see cref="T:System.Guid" />プロパティと比較する値を含むです。</param>
        <summary>
            プロパティ フィルター条件文字列を生成、<see cref="T:System.Guid" />値。
            </summary>
        <returns>書式付きフィルター条件を表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForInt">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForInt (string propertyName, string operation, int givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForInt(string propertyName, string operation, int32 givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForInt(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForInt (propertyName As String, operation As String, givenValue As Integer) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForInt : string * string * int -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForInt (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="propertyName">比較するプロパティの名前を含む文字列。</param>
        <param name="operation">使用する比較演算子を含む文字列。</param>
        <param name="givenValue"><see cref="T:System.Int32" />プロパティと比較する値を含むです。</param>
        <summary>
            プロパティ フィルター条件文字列を生成、<see cref="T:System.Int32" />値。
            </summary>
        <returns>書式付きフィルター条件を表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForLong">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForLong (string propertyName, string operation, long givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForLong(string propertyName, string operation, int64 givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForLong(System.String,System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForLong (propertyName As String, operation As String, givenValue As Long) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForLong : string * string * int64 -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.GenerateFilterConditionForLong (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="propertyName">比較するプロパティの名前を含む文字列。</param>
        <param name="operation">使用する比較演算子を含む文字列。</param>
        <param name="givenValue"><see cref="T:System.Int64" />プロパティと比較する値を含むです。</param>
        <summary>
            プロパティ フィルター条件文字列を生成、<see cref="T:System.Int64" />値。
            </summary>
        <returns>書式付きフィルター条件を表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Project&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T Project&lt;T&gt; (T entity, params string[] columns);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T Project&lt;T&gt;(!!T entity, string[] columns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.Project``1(``0,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Project(Of T) (entity As T, ParamArray columns As String()) As T" />
      <MemberSignature Language="F#" Value="static member Project : 'T * string[] -&gt; 'T" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.Project (entity, columns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="entity" Type="T" />
        <Parameter Name="columns" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="T">クエリのエンティティ型。</typeparam>
        <param name="entity">プロジェクトからログオフするエンティティのインスタンス。</param>
        <param name="columns">クエリの実行時に返されるエンティティのプロパティの名前を含む文字列オブジェクトの一覧です。</param>
        <summary>
            テーブルに対してクエリを実行時に返されるエンティティのプロパティの名前を指定します。 
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンス エンティティのプロパティを返すように設定します。</returns>
        <remarks>Project 句は、サーバーから返されるプロパティを制限するために使用、クエリでは省略可能です。 既定では、クエリは、エンティティから、すべてのプロパティを返します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery Select (System.Collections.Generic.IList&lt;string&gt; columns);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery Select(class System.Collections.Generic.IList`1&lt;string&gt; columns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.Select(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select (columns As IList(Of String)) As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Select : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery" Usage="tableQuery.Select columns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="columns">クエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を含む文字列オブジェクトの一覧です。</param>
        <summary>
            テーブル クエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を定義します。 
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンス テーブル エンティティのプロパティを返すように設定します。</returns>
        <remarks>Select 句は、サーバーから返されるテーブルのプロパティを制限するために使用、テーブルのクエリでは省略可能です。 既定では、クエリは、テーブル エンティティから、すべてのプロパティを返します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectColumns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SelectColumns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SelectColumns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableQuery.SelectColumns" />
      <MemberSignature Language="VB.NET" Value="Public Property SelectColumns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SelectColumns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.SelectColumns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはテーブルのクエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を設定します。
            </summary>
        <value>クエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を含む文字列のリスト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery Take (Nullable&lt;int&gt; take);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery Take(valuetype System.Nullable`1&lt;int32&gt; take) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.Take(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (take As Nullable(Of Integer)) As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Take : Nullable&lt;int&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery" Usage="tableQuery.Take take" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="take" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="take">テーブル クエリで返されるエンティティの最大数。</param>
        <summary>
            クエリから返されるエンティティの数の上限の境界を定義します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスのエンティティの数を返すように設定します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TakeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TakeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TakeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableQuery.TakeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TakeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TakeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery.TakeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはテーブルのクエリが返すエンティティの数を設定します。 
            </summary>
        <value>テーブル クエリで返されるエンティティの最大数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery Where (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery Where(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery.Where(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (filter As String) As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Where : string -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery" Usage="tableQuery.Where filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">テーブル クエリに適用するフィルター式を含む文字列。</param>
        <summary>
            テーブル クエリのフィルター式を定義します。 指定したフィルター式を満たすエンティティのみが、クエリによって返されます。 
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスのフィルターでエンティティを返すように設定します。</returns>
        <remarks>フィルター式の設定は省略可能です。既定では、テーブルのクエリでフィルター式が指定されていない場合、テーブル内のすべてのエンティティが返されます。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>