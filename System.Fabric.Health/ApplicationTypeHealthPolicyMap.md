<Type Name="ApplicationTypeHealthPolicyMap" FullName="System.Fabric.Health.ApplicationTypeHealthPolicyMap">
  <TypeSignature Language="C#" Value="public sealed class ApplicationTypeHealthPolicyMap : System.Collections.Generic.Dictionary&lt;string,byte&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationTypeHealthPolicyMap extends System.Collections.Generic.Dictionary`2&lt;string, unsigned int8&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationTypeHealthPolicyMap&#xA;Inherits Dictionary(Of String, Byte)" />
  <TypeSignature Language="F#" Value="type ApplicationTypeHealthPolicyMap = class&#xA;    inherit Dictionary&lt;string, byte&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.String,System.Byte&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.Byte</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>
            特定のアプリケーションの種類の異常なアプリケーションの最大パーセンテージを含むマップを定義します。 
            </para>
    </summary>
    <remarks>アプリケーションの種類の正常性ポリシー マップをクラスターの正常性評価時に使用して、特別なアプリケーションの種類を記述できます。 マップに含まれるアプリケーションの種類がグローバルではなく、マップでは、含まれている割合に対して評価されます<see cref="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />です。
            マップで指定されたアプリケーションの種類のアプリケーションは、アプリケーションのグローバル プールに対してはカウントされません。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationTypeHealthPolicyMap ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationTypeHealthPolicyMap.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            インスタンスを作成、<see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />クラスです。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (string appTypeName, byte value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Add(string appTypeName, unsigned int8 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationTypeHealthPolicyMap.Add(System.String,System.Byte)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (appTypeName As String, value As Byte)" />
      <MemberSignature Language="F#" Value="override this.Add : string * byte -&gt; unit" Usage="applicationTypeHealthPolicyMap.Add (appTypeName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appTypeName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte" />
      </Parameters>
      <Docs>
        <param name="appTypeName">
          <para>アプリケーションの種類名です。</para>
        </param>
        <param name="value">
          <para>最大パーセント異常なアプリケーション、アプリケーションの種類は許可します。 0 ~ 100 の範囲でなければなりません。</para>
        </param>
        <summary>
          <para>
            値として最大パーセントの異常なアプリケーションと、特定のアプリケーションの種類のマップ内のエントリを追加します。
            </para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>指定した割合の値は、0 から 100 までの整数値の範囲外でした。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationTypeHealthPolicyMap.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationTypeHealthPolicyMap.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            文字列表現を取得、<see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />です。
            </summary>
        <returns><see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>