<Type Name="SqlRuleAction" FullName="Microsoft.ServiceBus.Messaging.SqlRuleAction">
  <TypeSignature Language="C#" Value="public sealed class SqlRuleAction : Microsoft.ServiceBus.Messaging.RuleAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SqlRuleAction extends Microsoft.ServiceBus.Messaging.RuleAction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SqlRuleAction&#xA;Inherits RuleAction" />
  <TypeSignature Language="F#" Value="type SqlRuleAction = class&#xA;    inherit RuleAction" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.RuleAction</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="SqlRuleAction", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>に対して実行される SQL 言語ベースの構文で記述されたアクションのセットを表す、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlRuleAction (string sqlExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sqlExpression As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SqlRuleAction : string -&gt; Microsoft.ServiceBus.Messaging.SqlRuleAction" Usage="new Microsoft.ServiceBus.Messaging.SqlRuleAction sqlExpression" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">SQL 式です。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />指定された SQL 式を持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlRuleAction (string sqlExpression, int compatibilityLevel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression, int32 compatibilityLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.#ctor(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sqlExpression As String, compatibilityLevel As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SqlRuleAction : string * int -&gt; Microsoft.ServiceBus.Messaging.SqlRuleAction" Usage="new Microsoft.ServiceBus.Messaging.SqlRuleAction (sqlExpression, compatibilityLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="compatibilityLevel" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">SQL 式です。</param>
        <param name="compatibilityLevel">将来使用するために予約されています。 互換性レベルを示す整数値。 現在、ハードコーディングを 20 です。</param>
        <summary>新しいインスタンスを初期化、 <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> SQL 式との互換性レベルが指定したクラスです。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompatibilityLevel">
      <MemberSignature Language="C#" Value="public int CompatibilityLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CompatibilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlRuleAction.CompatibilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompatibilityLevel As Integer" />
      <MemberSignature Language="F#" Value="member this.CompatibilityLevel : int" Usage="Microsoft.ServiceBus.Messaging.SqlRuleAction.CompatibilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="CompatibilityLevel", Order=65538)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このプロパティは、将来の使用に備えて予約されています。 互換性レベルを示す整数値現在にハードコード 20 です。</summary>
        <value>互換性レベルを示す整数値</value>
        <remarks>このプロパティは、将来の使用に備えて予約されています。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.Messaging.BrokeredMessage Execute (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Execute(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.Execute(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Execute (message As BrokeredMessage) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="override this.Execute : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="sqlRuleAction.Execute message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />先、<see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />適用されます。</param>
        <summary>実行、<see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />オブジェクト。</summary>
        <returns>処理された <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> です。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">操作が現在の状態に対して無効である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlRuleAction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.SqlRuleAction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>ルール アクションの値を設定します。</summary>
        <value>ルール アクションの値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.Messaging.RuleAction Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.Messaging.RuleAction Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Preprocess () As RuleAction" />
      <MemberSignature Language="F#" Value="override this.Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.RuleAction" Usage="sqlRuleAction.Preprocess " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RuleAction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>前処理済み取得<see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" />式。</summary>
        <returns>プリプロセス<see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" />式。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.RuleActionException">ルールの action ステートメントが無効であるか、操作の最大許容数を超えた場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public override bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlRuleAction.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.SqlRuleAction.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>示す値を取得するかどうか、<see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />前処理が必要です。</summary>
        <value>SQL ルール アクション前処理; に必要な場合は true。それ以外の場合は false です。 現在常に true を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlExpression">
      <MemberSignature Language="C#" Value="public string SqlExpression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlExpression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlRuleAction.SqlExpression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlExpression As String" />
      <MemberSignature Language="F#" Value="member this.SqlExpression : string" Usage="Microsoft.ServiceBus.Messaging.SqlRuleAction.SqlExpression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=true, Name="SqlExpression", Order=65537)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>SQL 式を取得します。</summary>
        <value>SQL 式です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="sqlRuleAction.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>文字列表現を返します<see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />です。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sqlRuleAction.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>SQL 92 構文と規則に対する SQL 式を検証します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.RuleActionException">ルールの action ステートメントが無効であるか、操作の最大許容数を超えた場合にスローされます。</exception>
      </Docs>
    </Member>
  </Members>
</Type>