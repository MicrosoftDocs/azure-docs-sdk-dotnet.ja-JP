<Type Name="SqlFilter" FullName="Microsoft.Azure.ServiceBus.SqlFilter">
  <TypeSignature Language="C#" Value="public class SqlFilter : Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlFilter extends Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SqlFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlFilter&#xA;Inherits Filter" />
  <TypeSignature Language="F#" Value="type SqlFilter = class&#xA;    inherit Filter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.Filter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            これは、式の構成フィルターと、パブリッシュ/サブスクライブ パイプラインで実行されるアクションを表します。
            </summary>
    <remarks>
            A<see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />到着するメッセージのユーザー定義のプロパティとシステムのプロパティに対して、ブローカーで評価される SQL のような条件式を保持します。 すべてのシステム プロパティ (すべてのプロパティに明示的に示すで、<see cref="T:Microsoft.Azure.ServiceBus.Message" />クラス) を付ける必要があります<code>sys.</code>条件式にします。 SQL のサブセットを実装 (EXISTS) のプロパティの存在をテスト、null 値 (IS NULL)、論理 NOT/AND または OR、テスト関係演算子、数値の算術演算で単純なテキストのパターンを LIKE で一致します。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlFilter (string sqlExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SqlFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sqlExpression As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SqlFilter : string -&gt; Microsoft.Azure.ServiceBus.SqlFilter" Usage="new Microsoft.Azure.ServiceBus.SqlFilter sqlExpression" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">To be added.</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />クラスの指定の SQL 式を使用します。
            </summary>
        <remarks>Sql 式の最大許容長は、1024 文字です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SqlFilter.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.SqlFilter.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            フィルター式の値を設定します。
            </summary>
        <value>フィルター式の値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlExpression">
      <MemberSignature Language="C#" Value="public string SqlExpression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlExpression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SqlFilter.SqlExpression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlExpression As String" />
      <MemberSignature Language="F#" Value="member this.SqlExpression : string" Usage="Microsoft.Azure.ServiceBus.SqlFilter.SqlExpression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            SQL 式を取得します。
            </summary>
        <value>SQL 式です。</value>
        <remarks>Sql 式の最大許容長は、1024 文字です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SqlFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="sqlFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            文字列表現を返します<see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />です。
            </summary>
        <returns><see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>