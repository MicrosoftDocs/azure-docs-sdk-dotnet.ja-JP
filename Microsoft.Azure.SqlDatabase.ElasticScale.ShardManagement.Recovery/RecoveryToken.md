<Type Name="RecoveryToken" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken">
  <TypeSignature Language="C#" Value="public sealed class RecoveryToken : IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RecoveryToken extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RecoveryToken&#xA;Implements IEquatable(Of RecoveryToken)" />
  <TypeSignature Language="F#" Value="type RecoveryToken = class&#xA;    interface IEquatable&lt;RecoveryToken&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            回復のトークンが生成されのメソッドで使用される、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager" />シャードのマップの競合の検出と解決を実行します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As RecoveryToken) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; bool" Usage="recoveryToken.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="other">比較する RecoveryToken です。</param>
        <summary>
            他の等値比較を実行 RecoveryToken を指定します。
            </summary>
        <returns>True の場合は、同じ場所、false それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="recoveryToken.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">現在のオブジェクトと比較するオブジェクト。</param>
        <summary>
            指定したオブジェクトが現在のオブジェクトと等しいかどうかを判断します。
            </summary>
        <returns>指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="recoveryToken.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このインスタンスのハッシュ コードを計算します。
            </summary>
        <returns>オブジェクトのハッシュ コード。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="recoveryToken.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを文字列形式に変換します。
            </summary>
        <returns>オブジェクトの文字列表現。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>