<Type Name="RuleDescription" FullName="Microsoft.ServiceBus.Messaging.RuleDescription">
  <TypeSignature Language="C#" Value="public sealed class RuleDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RuleDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.RuleDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RuleDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type RuleDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RuleDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>規則の説明を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> クラスの新しいインスタンスを既定値で初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleDescription.#ctor(Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RuleDescription : Microsoft.ServiceBus.Messaging.Filter -&gt; Microsoft.ServiceBus.Messaging.RuleDescription" Usage="new Microsoft.ServiceBus.Messaging.RuleDescription filter" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="filter">メッセージと一致するために使用するフィルター式です。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" />指定したフィルター式を持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RuleDescription : string -&gt; Microsoft.ServiceBus.Messaging.RuleDescription" Usage="new Microsoft.ServiceBus.Messaging.RuleDescription name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">ルールの名前。</param>
        <summary>指定した名前を使用して、<see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (string name, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleDescription.#ctor(System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RuleDescription : string * Microsoft.ServiceBus.Messaging.Filter -&gt; Microsoft.ServiceBus.Messaging.RuleDescription" Usage="new Microsoft.ServiceBus.Messaging.RuleDescription (name, filter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="name">ルールの名前。</param>
        <param name="filter">メッセージと一致するために使用するフィルター式です。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" />指定された名前およびフィルター式を持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RuleAction Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.RuleAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleDescription.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As RuleAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.ServiceBus.Messaging.RuleAction with get, set" Usage="Microsoft.ServiceBus.Messaging.RuleDescription.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Action", Order=65538)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RuleAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージがフィルター式を満たす場合に実行するアクションを設定します。</summary>
        <value>メッセージがフィルター式を満たす場合に実行するアクション。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.RuleDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>ルールの作成時刻を取得します。</summary>
        <value>ルールの作成時間。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRuleName">
      <MemberSignature Language="C#" Value="public const string DefaultRuleName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultRuleName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultRuleName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultRuleName : string" Usage="Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トピック サブスクリプションを追加するときに既定の規則の作成に使用する既定の名前。 名前は、"$Default"です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.Filter Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.Filter Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleDescription.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As Filter" />
      <MemberSignature Language="F#" Value="member this.Filter : Microsoft.ServiceBus.Messaging.Filter with get, set" Usage="Microsoft.ServiceBus.Messaging.RuleDescription.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Filter", Order=65537)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Filter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージを照合に使用するフィルター式を設定します。</summary>
        <value>メッセージと一致するために使用するフィルター式です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">null (Visual Basic では Nothing) が割り当てられます。</exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RuleDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Messaging.RuleDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Name", Order=131077)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはルールの名前を設定します。</summary>
        <value>返します、<see cref="T:System.String" />ルールの名前を表すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>