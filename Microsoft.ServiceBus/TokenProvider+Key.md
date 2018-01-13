<Type Name="TokenProvider+Key" FullName="Microsoft.ServiceBus.TokenProvider+Key">
  <TypeSignature Language="C#" Value="protected internal class TokenProvider.Key : IEquatable&lt;Microsoft.ServiceBus.TokenProvider.Key&gt;" />
  <TypeSignature Language="ILAsm" Value=".class nested protected auto ansi beforefieldinit TokenProvider/Key extends System.Object implements class System.IEquatable`1&lt;class Microsoft.ServiceBus.TokenProvider/Key&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TokenProvider.Key" />
  <TypeSignature Language="VB.NET" Value="Protected Friend Class TokenProvider.Key&#xA;Implements IEquatable(Of TokenProvider.Key)" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.ServiceBus.TokenProvider+Key&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Key (string appliesTo, string claim);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string appliesTo, string claim) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (appliesTo As String, claim As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TokenProvider.Key : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key" Usage="new Microsoft.ServiceBus.TokenProvider.Key (appliesTo, claim)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="claim" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo">キーが対象アドレスを指定します。</param>
        <param name="claim">特定のユーザー、アプリケーション、コンピューター、またはその他のエンティティを指定します</param>
        <summary><see cref="T:Microsoft.ServiceBus.TokenProvider.Key" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.ServiceBus.TokenProvider.Key other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.ServiceBus.TokenProvider/Key other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.Equals(Microsoft.ServiceBus.TokenProvider.Key)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As TokenProvider.Key) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.ServiceBus.TokenProvider.Key -&gt; bool" Usage="key.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceBus.TokenProvider+Key" />
      </Parameters>
      <Docs>
        <param name="other">現在のオブジェクトと比較するキー。</param>
        <summary>指定したキーが現在のオブジェクトと等しいかどうかを判断します。</summary>
        <returns>指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="key.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">現在のオブジェクトと比較するオブジェクト。</param>
        <summary>指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</summary>
        <returns>指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="key.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>キーのハッシュ コードを返します。</summary>
        <returns>キーのハッシュ コード。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>