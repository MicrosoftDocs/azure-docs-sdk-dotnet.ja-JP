<Type Name="FabricClient+ClaimsRetrievalEventHandler" FullName="System.Fabric.FabricClient+ClaimsRetrievalEventHandler">
  <TypeSignature Language="C#" Value="public delegate string FabricClient.ClaimsRetrievalEventHandler(object sender, FabricClient.ClaimsRetrievalEventArgs e);" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed FabricClient/ClaimsRetrievalEventHandler extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ClaimsRetrievalEventHandler" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function FabricClient.ClaimsRetrievalEventHandler(sender As Object, e As FabricClient.ClaimsRetrievalEventArgs) As String " />
  <TypeSignature Language="F#" Value="type FabricClient.ClaimsRetrievalEventHandler = delegate of obj * FabricClient.ClaimsRetrievalEventArgs -&gt; string" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="sender" Type="System.Object" />
    <Parameter Name="e" Type="System.Fabric.FabricClient+ClaimsRetrievalEventArgs" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.String</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="sender">
      <para>参照、<see cref="T:System.Fabric.FabricClient" />インスタンスに、イベントが発生します。</para>
    </param>
    <param name="e">
      <para>イベント引数。</para>
      <seealso cref="T:System.Fabric.FabricClient.ClaimsRetrievalEventArgs" />
    </param>
    <summary>
            ClaimsRetrieval イベントを登録することによって、クレーム トークンの取得のコールバックを処理するためのデリゲート
            </summary>
    <returns>To be added.</returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>