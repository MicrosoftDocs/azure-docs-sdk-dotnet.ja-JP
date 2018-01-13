<Type Name="RuleAction" FullName="Microsoft.ServiceBus.Messaging.RuleAction">
  <TypeSignature Language="C#" Value="public abstract class RuleAction : System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RuleAction extends System.Object implements class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.RuleAction" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RuleAction&#xA;Implements IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type RuleAction = class&#xA;    interface IExtensibleDataObject" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Runtime.Serialization.IExtensibleDataObject</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RuleAction", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.EmptyRuleAction))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.SqlRuleAction))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.CompositeAction))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.RuleCreationAction))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.DateTimeOffset))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>フィルター式が一致するメッセージの変換で許可されているフィルター操作を表します。</summary>
    <remarks>
            フィルター式と一致しているメッセージの変換のためのフィルタ操作を許可します。 フィルター acions の一般的なユース ケースは、追加またはメッセージの相関 ID に基づくグループ ID の割り当てなど、メッセージに関連付けられているプロパティを更新することです。
            </remarks>
    <altmember cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />
    <altmember cref="T:Microsoft.ServiceBus.Messaging.EmptyRuleAction" />
  </Docs>
  <Members>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceBus.Messaging.BrokeredMessage Execute (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Execute(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleAction.Execute(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Execute (message As BrokeredMessage) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Execute : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="ruleAction.Execute message" />
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
        <param name="message">BrokeredMessage を入力します。</param>
        <summary>指定された BrokeredMessage でフィルター操作を実行します。</summary>
        <returns>ルール アクションの実行後に変更された BrokeredMessage です。</returns>
        <remarks>このクラスの具象実装は自由 InvalidOperationException をスローするのには、前処理が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceBus.Messaging.RuleAction Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.RuleAction Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleAction.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Preprocess () As RuleAction" />
      <MemberSignature Language="F#" Value="abstract member Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.RuleAction" Usage="ruleAction.Preprocess " />
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
        <summary>前処理、<see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" />オブジェクト。</summary>
        <returns>プリプロセス<see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" />オブジェクト。</returns>
        <remarks>このクラスの具象実装は自由 InvalidOperationException をスローするのには、前処理が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public abstract bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleAction.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.RuleAction.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>前処理を規則の操作が必要かどうかを示す値を取得します。</summary>
        <value>規則の動作は、前処理; が必要な場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Runtime.Serialization.IExtensibleDataObject.ExtensionData">
      <MemberSignature Language="C#" Value="System.Runtime.Serialization.ExtensionDataObject System.Runtime.Serialization.IExtensibleDataObject.ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject System.Runtime.Serialization.IExtensibleDataObject.ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleAction.System#Runtime#Serialization#IExtensibleDataObject#ExtensionData" />
      <MemberSignature Language="VB.NET" Value=" Property ExtensionData As ExtensionDataObject Implements IExtensibleDataObject.ExtensionData" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.Messaging.RuleAction.System.Runtime.Serialization.IExtensibleDataObject.ExtensionData" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Runtime.Serialization.IExtensibleDataObject.ExtensionData</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.ExtensionDataObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public abstract void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleAction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit" Usage="ruleAction.Validate " />
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
        <summary>文法に対するルールの処理を検証します。 </summary>
        <remarks>このクラスの具象実装は自由 InvalidOperationException をスローするのには、前処理が必要です。</remarks>
        <altmember cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />
      </Docs>
    </Member>
  </Members>
</Type>